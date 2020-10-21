# slack2iso

This script converts your Slackware Linux installation into an ISO image to start using a "livecd" system, which can be via pendrive or cdrom.

### Installation:  

You should only run slack2iso as **root!**  

```
chmod +x slack2iso.sh
```

### Options:

- **--help**: Display help.
- **--clean**: Clean the work folder.
- **--create**: Create the iso image.

### Example:

```
./slack2iso.sh --create
```

### Some considerations:

- All necessary folders and files, including the ISO image will be created in the "/iso" work folder.
- Your Slackware must be installed on a single partition. 
- EFI boot support.
- It has been tested on installations with Slackware64-current.
- It's still a development version, so be careful and make a backup first! ;)

----  
