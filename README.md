# CUstomPhpPayloadSignature (CUPPS)
Simple script to generate PHP payloads with custom file signatures to evade input sanitisation.

### How to use (beta)

```
usage: cupps.py [-h] [-s target_signature]

Script to create PHP Payloads with custom file signatures

optional arguments:
  -h, --help            show this help message and exit
  -s target_signature, --signature target_signature
                        accepted inputs : png,jpg,exe,elf,gif,bmp,jar,pdf,iso

~ with <3 by X64M

```

For Example : 

```sh
python cupps.py -s png
```

This will create the payload with png signature
