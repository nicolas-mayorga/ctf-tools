# ctf-tools
a few common tools/websites to help with CTFs

## Websites
[CyberChef](https://gchq.github.io/CyberChef/): analyse and decode data easily

[Image Metadata Viewer](https://pics.io/pdf-metadata-viewer): view image metadata quickly and easily

[Forensically - JPEG Analysis](https://29a.ch/photo-forensics/#forensic-magnifier): analyse jpegs, able to manipulate the image in different ways

[dCode](https://www.dcode.fr/en): decode ciphers

[HexEdit](https://hexed.it/): edit hexdumps easily

[StegOnline](https://georgeom.net/StegOnline/upload): stegonography stuff

[AperiSolve](https://www.aperisolve.com/): another stegonography site, does a lot of stuff at once

[QuipQiup](https://quipqiup.com/) cryptogram solver

## CL tools 

Quick example usage:
Steghide: steghide --extract -sf "filename.ext"

John the ripper: john -wordlist="filename.txt" -format="hash-mode" hashfile.txt <- use man john to see different hash-modes

