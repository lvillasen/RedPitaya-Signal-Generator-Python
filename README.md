# Python Scripts to Control the Arbitrary Signal Generator Module on a RedPitaya Board

The scripts were tested on 

- Version: 1.04
- Build: 18 

of the Red Pitaya GNU/Linux Ecosystem using Python 3.5.

These scripts use the *periphery module* which is already installed in the latest releases of the RedPytaya ecosystem.  

# HW Configuration
Connect IN1 to OUT1 on your RedPitaya board and the range jumper on IN1 to LV. If the periphery module is nor installed you may install it with the !pip install periphery command line on a new cell.

We will make extensive use the RedPitaya memory map, it may be consulted here:

## Installation

The simplest way to install the code is to clone the repository and copy the jupyter notebook called *ASG_Elephant.ipynb* to the directory /home/jupyter on the RedPitaya 

Then you can open it through the *Jupyter Python Programming* page from the *Development* page of the RedPitaya web page menu.

An alternative is to use an ssh-tunnel.

On the latest ecosystems Jupyter Notebook is already installed. Otherwise you need to install it.


## License

[MIT](LICENSE)
