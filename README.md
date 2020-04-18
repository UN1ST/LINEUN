# LINEUN
[![LICENSE](https://img.shields.io/badge/LICENSE-BSD%203%20Clause-blue?style=for-the-badge "LICENSE")](https://github.com/fadhiilrachman/line-py/blob/master/LICENSE) [![Supported python versions: 3.x](https://img.shields.io/badge/python-3.x-green.svg?style=for-the-badge "Supported python versions: 3.x")](https://www.python.org/downloads/)

Python lib for LINE unofficial messaging API.

## Usage
### Register LINE account
```python
from LINEUN import LINE
line = LINE()
line.registerWithPhoneNumber("Your phone number", "Your country code")
```
### Login to LINE account with QR Code
```python
from LINEUN import LINE
line = LINE()
line.loginWithQRCode()
```
### Login to LINE account with Mail
```python
from LINEUN import LINE
line = LINE()
line.loginWithMail("Your mail", "Your password")
```

## Author
UN1ST/[@UN1ST](https://github.com/UN1ST/)
