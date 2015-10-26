# whitemark
Steganographic encoding of a watermark in the whitespace of text.

##Usage
To encode `message` in the text of `input.txt`, producing `output.txt`:
```bash
$ ./whitemark message < input.txt > output.txt
```

To recover the message from `output.txt`:
```bash
$ ./whitemark < output.txt
```
