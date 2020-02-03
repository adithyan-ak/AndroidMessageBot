# AndroidMessageBot :robot:
Automated Android text messaging bot that uses android web messaging feature to send automated text messages to multiple contacts for a particular interval.

## Installation

```
git clone https://github.com/adithyan-ak/AndroidMessageBot.git
```

## Recommended Python Version:

The Bot supports **Python 3**.

* The recommended version for Python 3 is **3.8.x**

## Dependencies:

The Bot depends on the `Selenium` python module.

#### Selenium Module (https://selenium-python.readthedocs.io/)

- Install for Windows:
```
C:\python37\python3.exe -m pip install selenium
```

- Install using pip on Linux:
```
sudo pip3 install selenium
```
## Setup:

Edit the MessageBot.py file according to your needs. 

Add the contact names to whom you wish to send the message in ```names```(Tuple) variable of **Line 10**.

Add the Message which you wish to send to the selected contacts in ```Message``` variable of **Line 12**


## Execution:

You can run the Bot by executing the MessageBot.py file.

```
python3 MessageBot.py
```

## License

AndroidMessageBot is licensed under the GNU GPL license. take a look at the [LICENSE](https://github.com/adithyan-ak/AndroidMessageBot/blob/master/LICENSE) for more information.


## Version
**Current version is 1.0**

