# AES-256 Encryptor/Decryptor

![AESlogo](https://o.remove.bg/downloads/f0479a75-8aea-4f4b-b902-041f0d741f61/R-removebg-preview.png)

###

<h2 align="left">How to use?</h2>

1. Download zip file (Release/Beta vX.X)

2. unzip files

3. To use Encryption/Decryption feature you have to generate your own key using KeyGenerator.exe Just simply run it.
<b>(You must protect the key and not lose it, otherwise you cannot decrypt the files!)</b>

4. Generated file (key.secure) must be in the same directory as aese.exe

5. Both files (aese.exe and key.secure) must be in the same directory as the file you want to encrypt or decrypt

###

6. To run <b>encryption:</b>

```shell
aese filename
```
the console should give a message:

```shell
File filename encrypted.
```

###

7. To run <b>decryption:</b>

```shell
aese filename --decrypt
```
the console should give a message:

```shell
File filename decrypted.
```
<h3>Remember that encrypted files have the ending .aese added. When decrypting, you must remember to enter the full name of the file with this ending for it to work</h3>
