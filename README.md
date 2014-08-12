# cfb8

This package implements the CFB-8 cipher block mode. This differs from normal CFB8 (implemented in the builtin `cipher` package) in that the initialization vector is re-encrypted after encrypting every byte of plaintext, rather 
than every 16 bytes.

