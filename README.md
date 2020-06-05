# Build_times_LLVM_MySQL_qemu
Build times and build sizes of LLVM, MySQL-Server, qemu compared between Apple Clang 10.0.1 and clang 11.0.0




                  System Compiler (Apple Clang)                           LLVM Compiler
                  Build Time          Build Size                    Build Time          Build Size
                                      (on disk)                                         (on disk)

MySQL-Server      real	83m53.688s    941.04MB                      real	109m39.282s    951.2MB 
                  user	75m29.850s                                  user	99m43.071s
                  sys	5m41.172s                                     sys	6m13.283s



LLVM              real	72m0.505s     1.59GB                        real	97m59.186s     1.57GB
                  user	260m44.044s                                 user	356m12.425s
                  sys	11m3.760s                                     sys	12m28.626s



Qemu              real	6m48.850s     355.6MB                       real	8m34.970s      361.7MB
                  user	5m33.292s                                   user	7m10.967s
                  sys	1m2.211s                                      sys	1m1.773s
  


Apple Clang Version - Apple LLVM version 10.0.1 (clang-1001.0.46.4)

LLVM Compiler Version - clang version 11.0.0

LLVM Compiler Checkout hash - e5bb542362dfbb6c57a597810d740987afbc4202
				      (Wed May 27 21:13:08 2020)

Project Checkout hashes : 

MySQL-Server : 7d10c82196c8e45554f27c00681474a9fb86d137

LLVM : e5bb542362dfbb6c57a597810d740987afbc4202

Qemu : c86274bc2e34295764fb44c2aef3cf29623f9b4b


Machine Specs:

MacBook Air (Early 2015)
OS - macOS Mojave 10.14.6
Processor - 1.6 GHz Intel Core i5
Memory - 8 GB 1600 MHz DDR3
Graphics - Intel HD Graphics 6000 1536 MB

