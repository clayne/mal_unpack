# mal_unpack
Dynamic unpacker based on [PE-sieve](https://github.com/hasherezade/pe-sieve.git).<br/>
It deploys a packed malware, waits for it to unpack the payload, dumps the payload and kills the original process.</b><br/>
Usage:
```
mal_unpack.exe <path_to_the_malware> [timeout: ms]
```
<b>WARNING:</b> This unpacker deploys the original malware. Use it only on a VirtualMachine.

Latest builds*:
-
*those builds are available for testing and they may be ahead of the official [release](https://github.com/hasherezade/pe-sieve/releases):
+ [32-bit](https://goo.gl/ShvVWu)
+ [64-bit](https://goo.gl/92fx4P)
<hr/>
