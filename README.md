

# HOW TO GAIN ROOT ACCESS ON OVH VPS 
#### *YOU **MUST** OWN THE VPS*

*Bought an OVH and got given user `ubuntu` etc? Here's how to fix that issue.*

## Getting Started
* Type `sudo nano /etc/ssh/sshd_config`
* Scroll Down until you see `#PermitRootLogin prohibit-password` change that to `PermitRootLogin yes` then Save.
* Type `sudo your_password`
* Once that is done do `service sshd restart`
* Then login using user `root` and password `your_password`


Hope it works for you.

## Credits

* **vizxals** - [Reddit](https://www.reddit.com/r/ovh/comments/i095rj/ovh_doesnt_allow_root_access_anymore/g17be1r?utm_source=share&utm_medium=web2x&context=3) | [Twitter](https://twitter.com/Vizxals)
