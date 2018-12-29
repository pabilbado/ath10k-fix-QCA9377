# ath10k-fix-QCA9377
Fixed ath10k drivers for the Qualcomm Atheros QCA9377 card. After the latest update the drivers for the Qualcomm 9377 card would not load. This files should be able to solve that.

# How to
## Automatic
I added a script that when run as root will automatically fix it for you :)
## Manual
If you don't like other people's code running in your machine you can do it manually. But you can check the bash Script is just a small script that automates it for you. 
Substitute the folder QCA9377 in /lib/firmware/ath10k/ for the one in the repository, this should work. :)
