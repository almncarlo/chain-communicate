# chain-communicate

## Introduction

This project is meant to showcase concepts learned from a Data Structures & Algorithms class, mainly involving graphs and data visualization.

Say that we have 'agent codes' that represent people in the form of 4-character strings (i.e. MCJN, KOBT, LBJK, etc.) and this list of codes are essentially strings 'AAAA' to 'ZZZZ'. These 'agents' may want to communicate with each other, so an algorithm that can connect a sender of a message to its receiver must be devised. However, it cannot be just as simple as connecting a sender directly to a recipient as it may easily compromise the identities of both people. We can instead identify other agents between the sender and the receiver that can carry out the 'chain of communication' to make it harder for other people to identify who's talking.

One way of identifying the other 'intermediates' between the two agents would be relative to their codes' characters. For example, if agents AAAA and BJCK want to communicate, a chain must be established so that the message propagates from AAAA -> BAAA -> BJAA -> BJCA -> BJCK. For each new intermediate agent, one character from the original sender is changed to match that of the intended receiver.

### Part 1: Awaken, Sleeper Agents!

To identify this chain, a binary search tree will be used. 

### Part 2: CORE is the Center

WIP

### Part 3: Data Visualizations

WIP

## Codebase

This project was written in Python, and stored in one Jupyter Notebook in the main directory. 
