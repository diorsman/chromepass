chromepass
==========

Get all passwords stored by Chrome on WINDOWS.

#Information

Google Chrome stores all passwords you saved by pressing 'REMEMBER ME' in a database at 

``` Appdata\Local\Google\Chrome\User Data\Default\Login Data ```

It encrypts passwords with the Windows <b>CryptProtectData</b> function. 
You can find the encryptor at the [Chromium Github Page](https://github.com/chromium/chromium/blob/trunk/chrome/browser/password_manager/encryptor_win.cc)

#Run

To print output simply:
``` python chromepass.py ```


To write to csv file:
``` python chromepass.py --o ```

#Author

[Hassaan Ali Wattoo](https://twitter.com/hassaanaliw)
