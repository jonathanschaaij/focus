# focus
Block and unblock websites with a simple command

## Usage
To block all websites specified in the hosts/block file for XXX seconds:
```focus -b XXX```

To unblock all websites: ```focus -u```


### Functionality
This script works by changing the /etc/hosts file. This means writing permissions are needed for this script to work.

When blocking or unblocking websites the /etc/hosts file is replaced with the hosts/block or hosts/unblock files respectively. The hosts/blocktime file stores the time up to which the websites can't be unblocked using this script

This script is not ment as a secure way to prevent accessing websites. It's just a way for me to make it harder to get distraced, which should help me remain focused for longer. All other website-blockers have been too complicated to get started and too easy to disable for rendering them quite useless for me. This simple script makes it fast and easy to block the most distracting websites harder to unblock them in a fast way
