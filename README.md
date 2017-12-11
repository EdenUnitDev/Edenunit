# EdenUnit

# BEFORE USING EDENUNIT SIMPLEWALLET/DAEMON OR EDENUNIT GUI CLIENT:
## If your daemon is stuck on block 0, or if you do not have any peers, load up the daemon and start it like the following:
> ./edenunitd --add-peer 35.196.218.62:8080

Or

> ./edenunitd --add-peer 35.188.44.219:8080
## Doing this will manually connect you to the seed nodes to allow you to find more peers, if the daemon or GUI client is starting at block 0 exit both and open the daemon with that command, then you may continue to use simplewallet once it is done syncing, or once it is done syncing close the daemon and open up the GUI client and it should start getting blocks as it should normally

# THIS README FILE INCLUDES IN ORDER: POINT OF EDENUNIT, EDENUNIT COMPILE GUIDE

## What is EdenUnit?

EdenUnit is a peer to peer digital currency powered by the blockchain, the point of EdenUnit is simple, it's not to be the future
of digital currencys, nor is it meant to be the biggest currency out there, it is simply a testbed for new and innovative ideas for
cryptocurrencys, which you can read our many ideas on the EdenUnit site.

## Why use Cryptonote?

We chose Cryptonote for our coin because our developers are very used to the Cryptonote code base, and it is easily forkable. We want our coin to be easily forkable, because in the case we create a very innovative idea and implement it into our coin, we want developers everywhere to be able to use our code in their own coin, so they can use it to power their own currency ideas, or simply build off of what we started.

## Why are the coins specifications like this?

We chose the coinss emission speed to be 10 years for all coins to be mined, because this gives up development time to improve the first segement of the coin: The mining phase (as most coins will be on for a long while, we want to implement features in this time span that have to do with mining, for at least some features), when mining is done we will still create features for this coin, as this is an ongoing project. We chose block unlock window of 5 Blocks, because it is kinda annoying waiting the default 60 blocks or even 10 blocks to spend your coins.

## When will the EdenUnit project end?

As of now, there is no clear ending point for EdenUnit. Though we know for a fact, until we have made a great postive impact on the Crypto scene, the EdenUnit project will not end.

## Why the name EdenUnit?

We chose the name EdenUnit, because in the story of the Garden Of Eden, there is a tree of knowledge, and our logo is supposed to represent that. And since our project goal is to create a postive impact on the crypto scene by creating new innovative features that are easily forkable for other developers to use, we thought that by spreading knowledge, naming our project EdenUnit and having our logo be the Tree Of Knowledge was very fitting.











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

