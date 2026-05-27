```Shell
 ► 0x400ef2 <phase_1+18>               call   WELCOME                <entry_point>
        rdi: 0x402400 ◂— outsd dx, dword ptr [rsi] /* 'Nothing is in here' */
        rsi: 0x402400 ◂— outsd dx, dword ptr [rsi] /* 'jk there's more' */
   0x400ef7 <phase_1+23>               add    rsp, 8
   0x400efb <phase_1+27>               ret
────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────
pwndbg>

BOOM!!!
The BOMB HAS BEEN PLANTED.
[Inferior 1 (process 523) exited with code 010]
pwndbg>
```

Learning reverse engineering & low-level < security >

![Static Badge](https://img.shields.io/badge/Python-%233776AB?style=flat&logo=python&logoColor=white)![Static Badge](https://img.shields.io/badge/C%2FC%2B%2B-%2300599C?style=flat&logo=c%2B%2B&logoColor=white)
