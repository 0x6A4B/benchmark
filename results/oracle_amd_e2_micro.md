# Unixbench

Oracle AMD Micro E2 free instance 1/2. 1/8 OCPU

```
========================================================================
   BYTE UNIX Benchmarks (Version 5.1.3)

   System: instance-20250213-1407: GNU/Linux
   OS: GNU/Linux -- 6.8.0-1013-oracle -- #13-Ubuntu SMP Mon Sep  2 11:35:20 UTC 2024
   Machine: x86_64 (x86_64)
   Language: C.UTF-8 (charmap="ANSI_X3.4-1968", collate="ANSI_X3.4-1968")
   CPU 0: AMD EPYC 7551 32-Core Processor (3992.5 bogomips)
          Hyper-Threading, x86-64, MMX, AMD MMX, Physical Address Ext, SYSENTER/SYSEXIT, AMD virtualization, SYSCALL/SYSRET
   CPU 1: AMD EPYC 7551 32-Core Processor (3992.5 bogomips)
          Hyper-Threading, x86-64, MMX, AMD MMX, Physical Address Ext, SYSENTER/SYSEXIT, AMD virtualization, SYSCALL/SYSRET
   09:53:44 up 10 days, 21:41,  0 users,  load average: 0.72, 0.20, 0.06; runlevel

------------------------------------------------------------------------
Benchmark Run: Mon Feb 24 2025 09:53:44 - 10:18:06
2 CPUs in system; running 1 parallel copy of tests

Dhrystone 2 using register variables       11743631.2 lps   (10.0 s, 7 samples)
Double-Precision Whetstone                     1908.1 MWIPS (10.0 s, 7 samples)
Execl Throughput                                608.2 lps   (30.0 s, 2 samples)
File Copy 1024 bufsize 2000 maxblocks        169867.5 KBps  (30.0 s, 2 samples)
File Copy 256 bufsize 500 maxblocks           45640.4 KBps  (30.0 s, 2 samples)
File Copy 4096 bufsize 8000 maxblocks        514129.0 KBps  (30.0 s, 2 samples)
Pipe Throughput                              268910.3 lps   (10.0 s, 7 samples)
Pipe-based Context Switching                   8096.7 lps   (10.0 s, 7 samples)
Process Creation                                861.8 lps   (30.0 s, 2 samples)
Shell Scripts (1 concurrent)                   1299.1 lpm   (60.0 s, 2 samples)
Shell Scripts (8 concurrent)                    174.1 lpm   (60.1 s, 2 samples)
System Call Overhead                         293790.8 lps   (10.0 s, 7 samples)

System Benchmarks Index Values               BASELINE       RESULT    INDEX
Dhrystone 2 using register variables         116700.0   11743631.2   1006.3
Double-Precision Whetstone                       55.0       1908.1    346.9
Execl Throughput                                 43.0        608.2    141.4
File Copy 1024 bufsize 2000 maxblocks          3960.0     169867.5    429.0
File Copy 256 bufsize 500 maxblocks            1655.0      45640.4    275.8
File Copy 4096 bufsize 8000 maxblocks          5800.0     514129.0    886.4
Pipe Throughput                               12440.0     268910.3    216.2
Pipe-based Context Switching                   4000.0       8096.7     20.2
Process Creation                                126.0        861.8     68.4
Shell Scripts (1 concurrent)                     42.4       1299.1    306.4
Shell Scripts (8 concurrent)                      6.0        174.1    290.1
System Call Overhead                          15000.0     293790.8    195.9
                                                                   ========
System Benchmarks Index Score                                         234.0

------------------------------------------------------------------------
Benchmark Run: Mon Feb 24 2025 10:18:06 - 10:42:38
2 CPUs in system; running 2 parallel copies of tests

Dhrystone 2 using register variables        9444912.3 lps   (10.0 s, 7 samples)
Double-Precision Whetstone                     1814.9 MWIPS (9.6 s, 7 samples)
Execl Throughput                                558.0 lps   (30.0 s, 2 samples)
File Copy 1024 bufsize 2000 maxblocks        151303.9 KBps  (30.0 s, 2 samples)
File Copy 256 bufsize 500 maxblocks           40296.3 KBps  (30.0 s, 2 samples)
File Copy 4096 bufsize 8000 maxblocks        470293.6 KBps  (30.0 s, 2 samples)
Pipe Throughput                              251336.0 lps   (10.0 s, 7 samples)
Pipe-based Context Switching                  29265.6 lps   (10.0 s, 7 samples)
Process Creation                               1548.4 lps   (30.0 s, 2 samples)
Shell Scripts (1 concurrent)                   1382.3 lpm   (60.1 s, 2 samples)
Shell Scripts (8 concurrent)                    177.7 lpm   (60.4 s, 2 samples)
System Call Overhead                         275449.9 lps   (10.0 s, 7 samples)

System Benchmarks Index Values               BASELINE       RESULT    INDEX
Dhrystone 2 using register variables         116700.0    9444912.3    809.3
Double-Precision Whetstone                       55.0       1814.9    330.0
Execl Throughput                                 43.0        558.0    129.8
File Copy 1024 bufsize 2000 maxblocks          3960.0     151303.9    382.1
File Copy 256 bufsize 500 maxblocks            1655.0      40296.3    243.5
File Copy 4096 bufsize 8000 maxblocks          5800.0     470293.6    810.9
Pipe Throughput                               12440.0     251336.0    202.0
Pipe-based Context Switching                   4000.0      29265.6     73.2
Process Creation                                126.0       1548.4    122.9
Shell Scripts (1 concurrent)                     42.4       1382.3    326.0
Shell Scripts (8 concurrent)                      6.0        177.7    296.2
System Call Overhead                          15000.0     275449.9    183.6
                                                                   ========
System Benchmarks Index Score                                         257.3
```