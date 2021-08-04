## About

This repository [BioArchLinux] provides bioinformatics software for students and researchers working on biology and related subjects.

You can easily convert your VPS distribution to ArchLinux via [vps2arch](https://gitlab.com/drizzt/vps2arch), and install software via pacman.

The users of ArchLinux and any other distributions based on ArchLinux can use this repository.

## How to Use

Add following repository to `/etc/pacman.conf`

```
[BioArchLinux]
SigLevel = Never
Server = https://repo.malacology.net
```

## Acknowledgements

This repository is based on [aur-build](https://github.com/Aloxaf/aur-build). Thanks go to [Aloxaf](https://github.com/Aloxaf) for the contribution of aur-build and his help on the establishment of BioArchLinux repository.

