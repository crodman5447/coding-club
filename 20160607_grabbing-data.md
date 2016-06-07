## Grabbing data

*June 7, 2016*

![Alice-peaking](http://www.alice-in-wonderland.net/wp-content/uploads/1book2.jpg)

> "It's no use going back to yesterday, because I was a different person then."

> *Alice*

**To pull off MiSeq data:**

`ssh <username>@gold`

`cd /ahg/regev_miseq01`

**To pull off NextSeq data:**

`ssh <username>@gold`

`cd /ahg/regev_nextseq`

*Notes*

`Data02` accesses the "new" NextSeq (on the right)

`Data` accesses the "old" NextSeq (on the left)

**To acccess data in specific projects:**

`ssh <username>@gold`

`cd /ahg/regevdata/projects`

**To connect to dropbox:**

You first need to mount the file server "dropbox/dropbox":

1. Click on the desktop
2. Click and hold `command` + `K`
3. In the server address field, enter `smb://dropbox/dropbox`
4. Enter in your password

You can think of mounting a file server as analagous to inserting (aka. "mounting") a USB into your computer.

In Terminal:

1. Ensure that you are **not** connected through `ssh`
2. `cd /Volumes/dropbox`

*Notes*

bash is an interpreter and translates your commands into computer actions (ie. lets you "talk" to your computer)

ssh is also bash, you can think of this as a tunnel to remotely connect to a different computer via the internet.
