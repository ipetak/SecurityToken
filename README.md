# SecureTokenLogin
PHP script activates by taping the NFC tag on the back of an android phone with NFC ReTag application. NFC ReTag application enables sending and reciveing data using AJAX method triggered by NXP Mifare Ultralight tag ID. Using PHP random security token is generated which is then sent to the same android phone, later encrypted and saved with the NFC tag ID into a MySql database. Only with matching phone and tag can a user be granted access. 