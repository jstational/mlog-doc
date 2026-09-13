**these are from the** `mindustry.logic.LogicOp` and `mindustry.logic.ConditionOp` **enums**  

#### arithmetic:
* `+` internally `add`  
* `-` internally `sub`  
* `*` internally `mul`  
* `/` internally `div`  
* `//` internally `idiv`, integer division, extracts the quotient  
* `%` internally `mod`, modulo, extracts the remainder, but not mathematically (can return negative values)  
* `%%` internally `emod`, true modulo, extracts the remainder
* `^` internally `pow`  

#### bitwise:
* `<<` internally `shl`, convert to binary and shift left (multiply by 2 for each shift)  
* `>>` internally `shr`, convert to binary and shift right keeping the numbers sign  
* `>>>` internally `ushr`, convert to binary and shift right  
* `b-and` internally `and`, convert to binary and logical and each digit  