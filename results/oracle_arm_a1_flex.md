# Unixbench

Oracle ARM Flex A1 - 4 vcpu - 24 GB

```
   BYTE UNIX Benchmarks (Version 5.1.3)

   System: gaming-server: GNU/Linux
   OS: GNU/Linux -- 6.8.0-1019-oracle -- #20-Ubuntu SMP Fri Jan 17 21:19:50 UTC 2025
   Machine: aarch64 (aarch64)
   Language: en_US.utf8 (charmap="UTF-8", collate="UTF-8")
   CPU 0: ARM Neoverse-N1 (50.0 bogomips)
          CPU Features: fp asimd evtstrm aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm lrcpc dcpop asimddp ssbs
   CPU 1: ARM Neoverse-N1 (50.0 bogomips)
          CPU Features: fp asimd evtstrm aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm lrcpc dcpop asimddp ssbs
   CPU 2: ARM Neoverse-N1 (50.0 bogomips)
          CPU Features: fp asimd evtstrm aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm lrcpc dcpop asimddp ssbs
   CPU 3: ARM Neoverse-N1 (50.0 bogomips)
          CPU Features: fp asimd evtstrm aes pmull sha1 sha2 crc32 atomics fphp asimdhp cpuid asimdrdm lrcpc dcpop asimddp ssbs
   16:36:52 up 26 days, 20:50,  1 user,  load average: 0.20, 0.08, 0.03; runlevel 2025-01-28

------------------------------------------------------------------------
Benchmark Run: Mon Feb 24 2025 16:36:52 - 17:04:49
4 CPUs in system; running 1 parallel copy of tests

Dhrystone 2 using register variables       46856596.0 lps   (10.0 s, 7 samples)
Double-Precision Whetstone                     8592.1 MWIPS (9.9 s, 7 samples)
Execl Throughput                               2806.0 lps   (30.0 s, 2 samples)
File Copy 1024 bufsize 2000 maxblocks       1073425.0 KBps  (30.0 s, 2 samples)
File Copy 256 bufsize 500 maxblocks          316197.8 KBps  (30.0 s, 2 samples)
File Copy 4096 bufsize 8000 maxblocks       1965553.5 KBps  (30.0 s, 2 samples)
Pipe Throughput                             1905962.1 lps   (10.0 s, 7 samples)
Pipe-based Context Switching                 103116.6 lps   (10.0 s, 7 samples)
Process Creation                               4954.5 lps   (30.0 s, 2 samples)
Shell Scripts (1 concurrent)                   7622.4 lpm   (60.0 s, 2 samples)
Shell Scripts (8 concurrent)                   2606.4 lpm   (60.0 s, 2 samples)
System Call Overhead                        1419380.3 lps   (10.0 s, 7 samples)

System Benchmarks Index Values               BASELINE       RESULT    INDEX
Dhrystone 2 using register variables         116700.0   46856596.0   4015.1
Double-Precision Whetstone                       55.0       8592.1   1562.2
Execl Throughput                                 43.0       2806.0    652.6
File Copy 1024 bufsize 2000 maxblocks          3960.0    1073425.0   2710.7
File Copy 256 bufsize 500 maxblocks            1655.0     316197.8   1910.6
File Copy 4096 bufsize 8000 maxblocks          5800.0    1965553.5   3388.9
Pipe Throughput                               12440.0    1905962.1   1532.1
Pipe-based Context Switching                   4000.0     103116.6    257.8
Process Creation                                126.0       4954.5    393.2
Shell Scripts (1 concurrent)                     42.4       7622.4   1797.7
Shell Scripts (8 concurrent)                      6.0       2606.4   4344.1
System Call Overhead                          15000.0    1419380.3    946.3
                                                                   ========
System Benchmarks Index Score                                        1444.4

------------------------------------------------------------------------
Benchmark Run: Mon Feb 24 2025 17:04:49 - 17:32:46
4 CPUs in system; running 4 parallel copies of tests

Dhrystone 2 using register variables      186165831.7 lps   (10.0 s, 7 samples)
Double-Precision Whetstone                    34112.8 MWIPS (9.9 s, 7 samples)
Execl Throughput                               8026.6 lps   (30.0 s, 2 samples)
File Copy 1024 bufsize 2000 maxblocks       4070553.9 KBps  (30.0 s, 2 samples)
File Copy 256 bufsize 500 maxblocks         1241094.5 KBps  (30.0 s, 2 samples)
File Copy 4096 bufsize 8000 maxblocks       6382512.9 KBps  (30.0 s, 2 samples)
Pipe Throughput                             7553834.2 lps   (10.0 s, 7 samples)
Pipe-based Context Switching                 735141.4 lps   (10.0 s, 7 samples)
Process Creation                              13105.3 lps   (30.0 s, 2 samples)
Shell Scripts (1 concurrent)                  20181.0 lpm   (60.0 s, 2 samples)
Shell Scripts (8 concurrent)                   2776.1 lpm   (60.0 s, 2 samples)
System Call Overhead                        5638461.0 lps   (10.0 s, 7 samples)

System Benchmarks Index Values               BASELINE       RESULT    INDEX
Dhrystone 2 using register variables         116700.0  186165831.7  15952.5
Double-Precision Whetstone                       55.0      34112.8   6202.3
Execl Throughput                                 43.0       8026.6   1866.7
File Copy 1024 bufsize 2000 maxblocks          3960.0    4070553.9  10279.2
File Copy 256 bufsize 500 maxblocks            1655.0    1241094.5   7499.1
File Copy 4096 bufsize 8000 maxblocks          5800.0    6382512.9  11004.3
Pipe Throughput                               12440.0    7553834.2   6072.2
Pipe-based Context Switching                   4000.0     735141.4   1837.9
Process Creation                                126.0      13105.3   1040.1
Shell Scripts (1 concurrent)                     42.4      20181.0   4759.7
Shell Scripts (8 concurrent)                      6.0       2776.1   4626.8
System Call Overhead                          15000.0    5638461.0   3759.0
                                                                   ========
System Benchmarks Index Score                                        4802.5

```