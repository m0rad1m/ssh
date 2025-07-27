# SSH Setup Guide

## Add ssh passphrase to `ssh-agent`

Run `ssh-add ~/.ssh/<your-ssh-key>``` to add your passphrase permantly.

If relevant: ensure `ssh-agent` is running: `eval $(ssh-agent)`, and also add this line in your ~/.profile file and reboot.
