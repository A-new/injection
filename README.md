# EarlyBird injection
This is a POC for the EarlyBird injection technique as named by Cyberbit. More details here:
[Hackers Found Using A New Code Injection Technique to Evade Detection](https://thehackernews.com/2018/04/early-bird-code-injection.html)

Use:
1. Put the shellcode of your choice to the source file (the included one will pop cmd.exe)
2. Recompile
3. Run: EarlyBird.exe [any x64 binary]

# CtrlInject injection
This is a POC for the CtrlInjection found by enSilo:
[Ctrl-Inject](https://blog.ensilo.com/ctrl-inject)

Use:
1. Put the shellcode of your choice to the source file (the included one will pop calc)
2. Recompile
3. Run: EarlyBird.exe [PID of x64 Console Application which has a non default HandlerList (e.g.: cmd.exe)]
