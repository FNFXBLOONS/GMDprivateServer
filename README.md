# GMDprivateServer
## Geometry Dash Private Server
Basically a Geometry Dash Server Emulator

Supported version of Geometry Dash: 1.0 - 2.1 (so any version of Geometry Dash works, as of writing this [11th February 2017])

Required version of PHP: 5.4+ (tested up to 7.1.3)

### Setup
1) Upload the files on a webserver
2) Import database.sql into a MySQL/MariaDB database
3) Edit the links in GeometryDash.exe (some are base64 encoded since 2.1, remember that)

### Credits
Private Messaging system by someguy28 (even though he needed a ton of help from me... and by a ton I mean A TON)

Base for account settings by someguy28

Using this for XOR encryption - https://github.com/sathoro/php-xor-cipher - (incl/lib/XORCipher.php)

Jscolor (color picker in packCreate.php) - http://jscolor.com/

Most of the stuff in generateHash.php has been figured out by pavlukivan and Italian APK Downloader, so credits to them