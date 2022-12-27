# CrackFileGen

# gencasetoggle
File generators to help with password cracking

Creates a hashcat rule file output to stdout which toggles all the alpha characters in a password up to a specified length.

The usage is 'gencasetoggle nn' where 'nn' is the maximum length of password you want to toggle. The script is set to an upper limit of 24 characters but it wouldn't be difficult to modify the script to create a higher limit. 32 bit processors won't be able to go higher than 31 characters and 64 bit processors won't hanfle higher than 63 characters. As it stands, 24 characters is going to create a rule file with over eight million rules so increasing the value will massively increase your crack times.


# tri, triam, quad, quadam, pent, pentam

These scripts will generate LARGE dictionaries that consist of passwords that are formed with keyboard patterns. The tri* files relate to three adjacent keys, making a total of 15 character passwords, the quad* files relate to four adjacent key and the pent* files to five. The 'am' suffix refers to the American keyboard layout whereas the unsuffixed files relate to the UK keyboard layout.
