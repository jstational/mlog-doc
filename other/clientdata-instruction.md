### the Client Data instruction  
- **I MIGHT BE WRONG ABOUT THIS**
- help me find the `Call.clientLogicDataUnreliable/Reliable(LVar, LVar)` method!
---
the statement definition can be found at the **2005th** line of `mindustry.logic.LStatements`  
and the instruction definition can be found at the **2082th** line of `mindustry.logic.LExecutor`  
there is a map rule that governs whether this instruction is allowed `allowLogicData` (boolean)

---
i assume this instruction returns a value that was set by a plugin