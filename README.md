```
 _________________
| | ___________ |o|
| | ___________ | |
| | ___________ | |
| | ___________ | |
| |_____________| |
|     _______     |
|    |       |   ||
| DD |       |   V|
|____|_______|____|
```
# FloppyStash

Just a little stash about the floppy disks. Not much here. Just unzip the zip, copy the files over, and your done.

If a sector gets corrupted or you want to format a floppy and your on Linux, you can run this command to do so:

`dd if=<FloppyVariant> of=/dev/fda bs=4096`

__Note__: This command assumes that the floppy disk is at `A:`. Not great if you have `A:` and `B:`.

If you want to see the boot sector, simply install Hexyl and run this command:

`sudo head -c 512 /dev/fda | hexyl`

Archived OSes, programs, and more abandonware available at WinWorld:

www.winworldpc.com

__Note__: Apparently, WinWorld and it's CMS is in beta right now. My pref is to not use IPFS even though it has benifits.
