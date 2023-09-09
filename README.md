# Paperbackup - Backup and restore GPG keys on paper

## encode
Generates a document including the private key as text in one page and as qr codes in another page

### Usage:
```
./encode <YOUR_KEY_ID>
```
### Dependencies:
- qrencode
- gomplate
- prince

## decode
Generates an key file from a series of qr code images

### Usage:
```
./decode
```
### Dependencies
- zbarimg
