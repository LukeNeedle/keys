## Public Keys
This repository contains a copy of the OpenPGP public keys that I use to sign things.

> [!IMPORTANT]
> Before using the keys included in this repo, check their validity.
> Here are some ways that you can do that:
> 1. Check the git history
>     I won't remove keys from this repository, instead I will add a note to the table below. If a key is modified in the git history without a comment, don't trust it.
> 2. Check the signature of the commit that it was added in
>     All commits to this repository will be signed by `dev@lukeneedle.uk` (or `luke.needle@development.lukeneedle.uk` prior to T1750716900)
> 3. Check the mirrors
>     This repository is mirrored between my [github](https://github.com/LukeNeedle/keys) and [gitlab](https://gitlab.com/LukeNeedle/keys). Check that they both say the same thing (and everything is signed with the same key)
> 4. Check the key file signatures
>     Included in this repository are the public key files with a signature file alongside them. Each public key file has been signed by `root@keys.lukeneedle.uk`. Check that the signatures are valid.

> [!IMPORTANT]
> If the key files are updated, a note will be included here and a changelog will be updated (or created) - this changelog will be signed with the root key.

| Key                                       | Valid | Notes                                                                                   |
| :---------------------------------------- | :---: | :-------------------------------------------------------------------------------------: |
| email@keys.lukeneedle.uk.pub              | Yes   | T1750716900: Replaced old root signature with new signature                             |
| l.needle@lancaster.ac.uk.pub              | Yes   | T1750716900: Replaced old root signature with new signature and added new dev signature |
| ln.sec@development.lukeneedle.uk.pub      | Yes   | T1750716900: Replaced old root signature with new signature and added new dev signature |
| luke.needle@development.lukeneedle.uk.pub | Yes   | T1750716900: Replaced old root signature with new signature                             |
| dev@lukeneedle.uk.pub                     | Yes   | -                                                                                       |
| packaging@keys.lukeneedle.uk.pub          | Yes   | T1750716900: Replaced old root signature with new signature and added new dev signature |
| root@keys.lukeneedle.uk.pub               | Yes   | T1750716900: Replaced with new root key                                                 |
| security@keys.lukeneedle.uk.pub           | Yes   | -                                                                                       |

> [!NOTE]
> All of my keys are signed by my root key.
