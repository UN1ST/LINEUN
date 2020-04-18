# LINEUN
[![LICENSE](https://img.shields.io/badge/LICENSE-BSD%203%20Clause-blue?style=for-the-badge "LICENSE")](https://github.com/UN1ST/LINEUN/blob/master/LICENSE) [![Supported python versions: 3.x](https://img.shields.io/badge/python-3.x-green.svg?style=for-the-badge "Supported python versions: 3.x")](https://www.python.org/downloads/)

Python lib for LINE unofficial messaging API.

## Usage
```python
from LINEUN import LINE
line = LINE()
```
### Register LINE account
```python
line.registerWithPhoneNumber("Your phone number", "Your country code")
```
### Login to LINE account with QR Code
```python
line.loginWithQRCode()
```
### Login to LINE account with Mail
```python
line.loginWithMail("Your mail", "Your password")
```

## Author
UN1ST/[@UN1ST](https://github.com/UN1ST/)
