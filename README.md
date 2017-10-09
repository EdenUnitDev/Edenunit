# edenunit-master
# EDENUNIT SIMPLEWALLET/DAEMON COMPILE GUIDE

This guide is assuming you are running Ubuntu, replace the download commands to the one corresponding to your OS.
If your on windows just download the windows binarys, no need to compile :D

## Install dependencies

> sudo apt-get install build-essential git cmake libboost1.55-all-dev

## Clone the simplewallet and daemon source

> git clone https://github.com/EdenUnitDev/edenunit-master

## CD into directory

> cd edenunit-master

## Compile the simplewallet/daemon

> Just type in "make" while in edenunit-master

Note: The compile may take a while

## Once done compiling, open the daemon

The daemon will now start to sync with the blockchain, this may take up to several hours depending on the blockchain height.
Once that is done open the simplewallet and create a new wallet, and now you have an EdenUnit Wallet! :D 
Type Help for commands, and type "start_mining [your address]" to begin to solo mine.

