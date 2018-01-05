**PLEASE NOTE: I no longer actively maintain this project. Pull requests are welcome, but development has halted and issues are unlikely to gain a response.**

# cfb8

This package implements the CFB-8 cipher block mode. This differs from normal CFB (implemented in the builtin `cipher` package) in that the initialization vector is re-encrypted after encrypting every byte of plaintext, rather 
than every 16 bytes.
