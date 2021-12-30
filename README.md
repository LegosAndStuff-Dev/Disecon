
# Disecon

![PyPI](https://img.shields.io/pypi/v/Disecon?color=gree) ![PyPI - License](https://img.shields.io/pypi/l/Disecon?color=gree)

#

Disecon is a python economy library where you could make a full economy system really easy.

## Installing

```
# Windows

pip install Disecon

# Lunix / Mac

python3 -m pip install Disecon
```
## Usage

### Starting Disecon

To start Disecon you need to do the following command bellow so that the database gets made. After you do the command you can delete the line that the command is on.

```python
from Disecon import *

start()
```

### Adding money

If you want to add some money into someones wallet you can follow the example bellow to add some money.

```python
from Disecon import *

wallet = money.wallet(amount=100, user_ID=Discord User ID)

wallet.add()
```

If you want to add some money into someones bank you can follow the example bellow to add some money. 

```python
from Disecon import *

bank = money.bank(amount=100, user_ID=Discord User ID)

bank.add()
```

### Subtracting money

If you want to subtract money from someones wallet do the following example bellow.

```python
from Disecon import *

wallet = money.wallet(amount=100, user_ID=Disecon User ID)

wallet.sub()
```

If you want to subtract money from someones bank you could follow the example bellow.

```python
from Disecon import *

bank = money.bank(amount=100, user_ID=Discord User ID)

bank.sub()
```