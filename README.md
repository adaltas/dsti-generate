
# MyProject

Generate datasets with random data.

Main functionnalites:
- Lot of customisation options
- Generate multiple tables
- ...

## Usage

Run './bin/generate help' print:

```
NAME
    generate - Generate datasets with random data.

SYNOPSIS
    generate [options]

OPTIONS
    -h --help               Display help information

COMMANDS
    users                   Generate users
    products                Generate products

EXAMPLES
    masson user list --help Show this message
```

## Developer

1. Open a bash terminal or use the 'bash' command within another terminal
    - Note that you'll need to have the windows subsystem feature activated (search for Windows features and turn on)
2. Use the command 'sudo apt-get update'
3. Use the command 'sudo apt install nodejs'
4. Use the command 'sudo apt install npm'
5. Remember to only use LF (unix) line ending characters on git commit.

How to customize/initialize the environmment (conf files, docker images...)
Undestanding the project layout
...

How to run the tests:

```
# All the tests
npm test
# Selected tests
npx mocha test/*.coffee
```