# RoHack99
A roblox exploit by capthehacker99

RoHack99 is a full lua 7 script executor.

It also has an interesting mod feature that allows user to use.

The mod API:

Globals:
  Memory : TABLE :
    SigScan : FUNCTION : --Scans a sig in the code format
    SigScanCallFunction : FUNCTION : --Scans a sig and get the function address from the call instruction
    ReadMemory : FUNCTION : --Read a memory address
    WriteMemory : FUNCTION : --Write a memory address
    ReadMemory_s : FUNCTION : --Safely Read a memory address (SLOW) returns zeros if an error occured
    WriteMemory_s : FUNCTION : --Safely Write a memory address (SLOW)
 ScriptContext : NUMBER : --The script context address given by RoHack99
 GetLuastate : FUNCTION : --Get a new luastate
 
