  
# About:
A free sniper bot built to work with Pancakeswap. Honeypot/rug checker built in. Bot allows you to compete with other trading bots when buying a token on PancakeSwap. Its faster than traditional bots because it watches the txpool/mempool where transactions are still "pending" on the BSC network. It will watch for when liquidity is added as a pending transaction and immediately submit your order, so that hopefully you get in right after liquidity is added and before everyone else.



# Installation:
### Download and install Python from the [site](https://www.python.org/downloads/).

If you download from the site it is important to tick the option "add python
to path".

### Download the code as a zip file and extract it.

### Copy the path of the bot directory

### Open the terminal.

Press the windows key + R and type "cmd":

### cd into the bot directory:
Type the command:

```
cd <path you copied>
```

### Install the dependencies:

```
pip install -r requirements.txt
```

### It is finished! Now to run the bot you just need to type:

```
python index.py
```


# How to use?

Open the terminal, cd into the folder if you haven't yet:

```
"cd" + path
```

To run it use the command

```
python index.py
```

As soon as you start the bot it will send the heroes to work. For it to work the game window needs to be visible.
It will constantly check if it needs to login or press the "new map" button. 
From 15 to 15 min it will send all heroes to work again


# Send home feature:

## How to use it:
Save a screenshot of the heroes you want to be sent home in the directory: /targets/heroes-to-send-home


## How it should behave:
It will automatically  load the screenshots of the heroes when starting up.
After it clicks in the heroes with the green bar to send them to work, it will look if there is any of the heroes that are saved in the directory in the screen.
If tit finds one of the heroes, the bot checks if the home button is dark and the work button is not dark.
If both these conditions are true, it clicks the home button.



