# Awesome-Terminal-Security
About Terminal-Security(Windows/IOS/Linux/Android)

## guideline

> Terminal security engineer (non-standard classification)

1. Junior Engineer：Proficient in using tools and scripts
2. Intermediate Engineer：Proficient in reading machine codes
3. Senior Engineer：Familiar with confrontation and bypass, as well as principles
4. Experienced Engineer：Familiar with developing complex scripts, tools, and weapons
5. Expert Engineer：Familiar with advanced technology(eg:taint analysis,symbolic execution, AI)

## Tools

### Packet Capture tool

> based on ISO TCP/IP

- Application Layer: [Fiddler](https://www.telerik.com/fiddler), [Charles](https://www.charlesproxy.com/), [BurpSuite](https://portswigger.net/burp), [MitmProxy](https://mitmproxy.org/), [AnyProxy](https://github.com/alibaba/anyproxy)、[ProxyMan(only mac)](https://proxyman.io/)
- Transport Layer: HttpCarry(only android), [postern](https://github.com/postern-overwal/postern-stuff), Drony
- Network Layer：[Wireshark](https://www.wireshark.org/), [eCapture](https://github.com/gojue/ecapture)
- Network Interface Layer: [tcpdump](https://www.tcpdump.org/)

### Analysis tools

- Decompiling tools
    - C Language Family: [IDA Pro](https://hex-rays.com/ida-pro/), [ghrida](https://ghidra-sre.org/)
    - Java: JD-GUI, [jadx](https://github.com/skylot/jadx)
    - Android: [apktool](https://github.com/iBotPeaches/Apktool), [JEB](https://www.pnfsoftware.com/), [GJoy Dex Analyzer(GDA)](http://www.gda.wiki:9090/)

- DisAssembler Tools
    - Hopper
    - radare2

- Machine code viewer
    - 010 editor
    - [visual studio code](https://code.visualstudio.com/)

### Debug tool

- Xposed Family: [Xspoed](https://github.com/rovo89/Xposed), [LSPosed](https://github.com/LSPosed/LSPosed)
- Frida Family: [frida](https://github.com/frida/frida), [objection](https://github.com/sensepost/objection), 
[jnitrace](https://github.com/chame1eon/jnitrace)

### Simulate execution tools

- [angr · A powerful and user-friendly binary analysis platform!](https://angr.io/)
- [capstone-engine · The Ultimate Disassembly Framework](https://www.capstone-engine.org/)
- [unicorn](https://www.unicorn-engine.org/)
- [Keystone – The Ultimate Assembler](https://www.keystone-engine.org/)


### Symbolic execution tools

[The Z3 Theorem Prover](https://github.com/Z3Prover/z3)

### taint analysis tools
> todo
 
