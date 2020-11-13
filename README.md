# Vending Machine

This project simulates a vending machine by allowing the user to purchase an item when the appropriate amount of money is inserted, if not will return all of the users money. It also stores money into an internal banking system that resets after the machine is *full* and stores all gain into the owner of the vending machines bank. The machine also refills the items inside when it is empty, sadly does not keep a log of the amount of each item sold for data analysis, but it restocks itself.

## Options

This project allows options to be accessed by the owner to simulate a secret code only accessible to the owner. These commands include:

`Product`

`Bank`

`Savings`

* Product will show the owner the current amount of product availale in the vending machine
* Bank will show the owner the current amount and type of money in the vending machine
* Savings will show the current amount of money that is considered gain

## Makefile

To run this file go to terminal and `cd` to the file and once there type the command `ls` into the terminal and you should see all the java files, a makefile and this README file.

Once in that file, you can use the following commands :

`make`

`make run`

`make clean`

* make will compile the code
* make run will run the code
* make clean cleans the folder of all unnecessary files
