This is a Sui Move languages introduction note

Sui Move is an open source language for writing safe smart contracts. It is a Sui's dialect of Move, which was originally developed at Facebook to power the Diem blockchain

First, you'll need to check that you have Sui installed.
Run the command below in the terminal
```
sui --version
```
If the Sui is not installed, refer Sui's docs to install (https://docs.sui.io/build/install)

Note:
`sui move new` command is used to initialise a Sui Move package.

e.g: `sui move new quest_3` This will initialize an empty Sui Move package with the name quest_3.


To compile and run unit testing of created move module.

To change the directory of your terminal to enter the quest_3 folder
```
cd quest_3
```
To compile the move modules
```
sui move build
```

To run the unit test
```
sui move test
```



