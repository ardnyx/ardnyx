```Python
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
## 
Learning reverse engineering & low-level < security >
- currently studying `deeper`: Operating Systems, Computer Systems, x86_64 Assembly
- capture-the-flag player (prioritizing reverse engineering)

```diff
- Planning to develop my own (buggy, but functional) Type 1 Hypervisor 
+ Finish the HTB CDSA (Certified Defensive Security Analyst) Path 
! ⚡ Finish CSAPP / OSTEP 
```
## ctf tracker
```text
📂 ardnyx/ctf-writeups
├── 🚩 picoCTF [2 Completed]
│   ├── Gatekeeper (Medium)
│   ├── WinAntiDbg0x100 (Medium)
│   └── perplexed (ONGOING)
│
├── 🟩 HackTheBox [1 Ongoing]
│   └── Behind The Scenes (ONGOING)
│
└── 🔵 cmu-bomb-lab (special)
    ├── bomb (phase_4)
    └── bomb.c
```

![Static Badge](https://img.shields.io/badge/Python-%233776AB?style=flat&logo=python&logoColor=white) ![Static Badge](https://img.shields.io/badge/C%2FC%2B%2B-%2300599C?style=flat&logo=c%2B%2B&logoColor=white) ![Static Badge](https://img.shields.io/badge/Kali-%23557C94?style=flat&logo=kalilinux&logoColor=white) ![Static Badge](https://img.shields.io/badge/django-%23092E20?style=flat&logo=django&logoColor=white) ![Static Badge](https://img.shields.io/badge/Ubuntu-%23E95420?style=flat&logo=ubuntu&logoColor=white) ![Static Badge](https://img.shields.io/badge/WSL2-%23FCC624?style=flat&logo=linux&logoColor=black) ![Static Badge](https://img.shields.io/badge/Docker-%232496ED?style=flat&logo=docker&logoColor=white) ![Static Badge](https://img.shields.io/badge/Proxmox-%23E57000?style=flat&logo=proxmox&logoColor=white) ![Static Badge](https://img.shields.io/badge/Arduino-%2300878F?style=flat&logo=arduino&logoColor=white) ![Static Badge](https://img.shields.io/badge/Neovim-%2357A143?style=flat&logo=neovim&logoColor=white) ![Static Badge](https://img.shields.io/badge/GDB-%23A42E2B?style=flat&logo=gnu&logoColor=white) ![Static Badge](https://img.shields.io/badge/Github%20Actions-%232088FF?style=flat&logo=githubactions&logoColor=white) ![Static Badge](https://img.shields.io/badge/Google%20Colab-%23F9AB00?style=flat&logo=googlecolab&logoColor=white)



