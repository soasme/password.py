password.py
===========

If you don't memory your password often, you will forget it quickly.
That's why I hate 1Password-alike Apps.

`password.py` forces you to generate password every time you use it.
You will never forget it until Alzheimer's coming.

* Save script and write your own password strategy.
* Type an universal salt and make sure it's a word only in your brain.
* Use product as another salt if you like.
* Type your password.
* Type strategy name you just wrote.

`password.py` generates

* one password for one website or app.
* a password hard to remember via some hints easy to remember.

### Useage

    # sudo pip install click # if it's your first running.
    $ python password.py
    Salt:
    Product:
    Password:
    Strategy:
    Password has pasted to your clipboard!

### TODO

* Linux
* Windows
* iOS
* Android
