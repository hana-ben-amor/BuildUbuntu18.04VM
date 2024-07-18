# Packer Ubuntu Virtualbox

- [Packer Ubuntu Virtualbox](#packer-ubuntu-virtualbox)
  - [Overview](#overview)
  - [Usage](#usage)
    - [Ubuntu 18.04.6](#ubuntu-18046)


## Overview

A packer template to create Ubuntu Server images (.ova) for VirtualBox.

**DISCLAIMER:** Packer will copy your **ED25519** public key to provide public-key-based ssh access.


## Usage

```bash
packer build ubuntu.pkr.hcl
```

The ova file will be placed on `output3/` directory


### Ubuntu 18.04.6
Tested with [packer][] 1.11.1, [VirtualBox][] 7.0.20

[Packer]: https://packer.io/
[VirtualBox]: https://www.virtualbox.org/
