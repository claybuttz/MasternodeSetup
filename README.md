# MasternodeSetup


### For Ubuntu-16.04
Required:
1. SAP Coins for Collateral
2. Local Wallet: https://github.com/Sappcoin-com/SAPP/releases
3. VPS with Ubuntu 16.04

VPS Commands:

wget -q https://raw.githubusercontent.com/SappCoin-com/MasternodeSetup/master/install-sapp-linux-16.04.sh <br>
sudo chmod +x install-sapp-linux-16.04.sh <br>
./install-sapp-linux-16.04.sh

### For Ubuntu-18.04
Required:
1. SAP Coins for Collateral
2. Local Wallet: https://github.com/Sappcoin-com/SAPP/releases
3. VPS with Ubuntu 18.04

VPS Commands:

wget -q https://raw.githubusercontent.com/SappCoin-com/MasternodeSetup/master/install-sapp-linux-18.04.sh <br>
sudo chmod +x install-sapp-linux-18.04.sh <br>
./install-sapp-linux-18.04.sh


### New Scripts

1. masternodeinstall.sh
2. masternodeinstall_beer.sh
3. masternodeinstall_verbose_and_debug.sh
<br>

**_The new additional scripts are tested on a FRESH Hetzner VPS with Ubuntu 16.04 and Ubuntu 18.04 operating systems. Although it should work with all VPS hosts you should test it before using it. It's better to use the scripts on a FRESH server instead of using them on an already masternode installed server but the latter case should work as well._**<br>
**_Scripts MUST be run as root (administrator) user on Ubuntu Linux OS._**<br>
**_The addional scripts are not coded for the distributions other then Ubuntu. Please open a issue ticket if you want to use the scripts on other Linux distributions._**<br>
**_All additional scripts works for both Ubuntu 18.04 and Ubuntu 16.04. They detect the operating system and installs the masternode accordingly. The script that has the term "beer" has beer icons coded in it and presenting them so it's not suitable for users below age of 18._**<br>

### Installation of Sapphire Coin Masternode and usage of script

To install Sapphire Coin Masternode use the following command:
```bash
bash <( curl -sL https://raw.githubusercontent.com/bedri/MasternodeSetup/master/masternodeinstall.sh)
```

or you can also use this _while drinking beer_ (![+18](https://placehold.it/15/f03c15/000000?text=+) **`+18`**)

```bash
bash <( curl -sL https://raw.githubusercontent.com/bedri/MasternodeSetup/master/masternodeinstall_beer.sh)
```

For seeing verbose output (the output of all the commands) use the command:
```bash
bash <( curl -sL https://raw.githubusercontent.com/bedri/MasternodeSetup/master/masternodeinstall_verbose_and_debug.sh)
```
