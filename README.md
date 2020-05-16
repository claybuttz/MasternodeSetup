# Sapphire Coin (SAPP) Masternode Installation Scripts 

#### masternodeinstall.sh<br>
This script installs the masternode for both Ubuntu v16.04 and Ubuntu v18.04. <br>
It has a progress bar for long processes.<br>
No raw command output is shown in this script output.<br>

#### masternodeinstall_beer.sh<br>
This script installs the masternode for both Ubuntu v16.04 and Ubuntu v18.04. <br>
It has a progress bar with a "glass of beer" icon for fun. <br>
It's not suitable for users under age of 18.<br>
No raw command output is shown in this script output.<br>

#### masternodeinstall_verbose_and_debug.sh<br>
This script installs the masternode for both Ubuntu v16.04 and Ubuntu v18.04.<br>
It has a progress bar for long processes. <br>
All raw command outputs is shown while running this script for debugging the process of masternode installation steps.<br>
<br>

**_The new additional scripts are tested on a FRESH Hetzner VPS with Ubuntu 16.04 and Ubuntu 18.04 operating systems. Although it should work with all VPS hosts you should test it before using it. It's better to use the scripts on a FRESH server instead of using them on an already masternode installed server but the latter case should work as well._**<br>
**_Scripts MUST be run as root (administrator) user on Ubuntu Linux OS._**<br>
**_The addional scripts are not coded for the distributions other then Ubuntu. Please open a issue ticket if you want to use the scripts on other Linux distributions._**<br>
**_All additional scripts works for both Ubuntu 18.04 and Ubuntu 16.04. They detect the operating system and installs the masternode accordingly. The script that has the term "beer" has beer icons coded in it and presenting them so it's not suitable for users below age of 18._**<br>

### Installation of Sapphire Coin Masternode and usage of scripts

To install Sapphire Coin Masternode use the following command:
```bash
bash <( curl -sL https://raw.githubusercontent.com/sappcoin-com/MasternodeSetup/master/masternodeinstall.sh)
```

or you can also use this _while drinking beer_ (![+18](https://placehold.it/15/f03c15/000000?text=+) **`+18`**)

```bash
bash <( curl -sL https://raw.githubusercontent.com/sappcoin-com/MasternodeSetup/master/masternodeinstall_beer.sh)
```

For seeing verbose output (the output of all the commands) use the command:
```bash
bash <( curl -sL https://raw.githubusercontent.com/sappcoin-com/MasternodeSetup/master/masternodeinstall_verbose_and_debug.sh)
```
