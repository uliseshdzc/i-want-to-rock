# I want to rock!
This repository implements examples of the [Rockstar](https://codewithrockstar.com/) programming language. It contains the following files:

- `i-want-to.rock`: Outputs the message "I want to rock!".


## Setup
Launch the following commands to setup the environment ([npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) must be installed).
```bash
npm install --global yarn
git clone https://github.com/RockstarLang/rockstar 
cd rockstar/satriani
yarn install
yarn pegjs
```

## Launch a program
To launch a program, use the following commands:
```bash
cd rockstar/satriani
node rockstar "../../<PROGRAM_NAME>.rock"