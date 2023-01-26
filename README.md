# Pdf-Encryptor

requirements
```
$ pip install PyPDF4==1.27.0 pyAesCrypt==6.0.0
```

syntax

``` python
python pdf.py < input-file > -a < action > -l < level > -p < password > -o < output-file >
```
input file - the file you want to encrypt or decrypt

action - decrypt or encrypt

level - level 1 or 2, level 1 - encrypts the file using a password, level 2 - encrypts the file using a encryption algorithm and a password

password - the password you want to keep if none specified will ask for the password

output file - the output file
