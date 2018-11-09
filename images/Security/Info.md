The photos in this folder show the sha1sum for trusted SD cards  

Sha1sum_nonencrypted_SD_with_Full_Setup.jpg  
The sum above is for a card will all the necessary software needed to use the PrivateKeyVault.  
I never use the card except to clone it.  
So the sum should never change.  
Any card I distribute cloned from this original will also have the same sha1sum.  
LUKS full disk encryption is not applied to the card.  
This allows the recipient to encrypt the card for himself or herself which is the only way to set the password for the LUKS encrypted partition.  
[Follow these instructions to apply LUKS full disk encryption.](https://github.com/johnshearing/PrivateKeyVault#setup-luks-full-disk-encryption) 
