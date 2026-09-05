# jam - Just A Manager, duh?
### version 1.8 (Praying MANtis)

## Usage:
	jam install <pkg> / jam install <pkg> <pkg> ## and so on 	Install apps
	jam remove <pkg> / jam remove <pkg> <pkg> ## and so on  	Remove apps
	jam update                                              	Refresh the APT package index
	jam upgrade                                            		Upgrade apps (if available)

### Aliases are stored in ~/.ayfam/jam/custom_packages.json

## Installation:

It only takes 1, JUST 1 step:

Run ```mkdir -p $HOME/.ayfam/jam && curl -sL "https://raw.githubusercontent.com/Fusion-AyFam-Company/jam-package-mgr/refs/heads/main/help.txt" -o $HOME/.ayfam/jam/help.txt && curl -sL "https://github.com/Fusion-AyFam-Company/jam-package-mgr/releases/download/RELEASE/jam_1.8_release.deb" -o /tmp/jam.deb && sudo apt install /tmp/jam.deb && rm /tmp/jam.deb``` 

#### This is long because it handles the installation and help.txt downloads.

## Other:

Edit ```~/.ayfam/jam/custom_packages.json``` to give different aliases for packages.

For ex.

```{"nm"; "network-manager"}```

will make

```jam install nm```

as

```apt-get install network-manager```

without it:

```jam install nm```

returns: 

```jam: Unknown command, this might be a typo, or this command does not exist.```
``` usage: jam {install or remove or update or upgrade}```

### Check ln. 46, 47 on jam

## Credits:

Built by justayyyyy (www.github.com/justayyyyy)
Built in the Shell language
For Linux distros that support APT
Built at Sep 2, 19:18, IST.

If you face any bugs, consider making a issue in the JAM repo. (www.github.com/Fusion-AyFam-Company/jam-package-mgr/)

This project is Open Source, meaning anyone can edit the code, so feel free to edit the code!

~ @justayyyyy (FALOOODA!!!)
