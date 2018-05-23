# Learn Blockchains by Building One

[![Build Status](https://travis-ci.org/dvf/blockchain.svg?branch=master)](https://travis-ci.org/dvf/blockchain)

# What is Blockchain

A block chain is a transaction database shared by all nodes participating in a system based on the Bitcoin protocol. A full copy of a currency's block chain contains every transaction ever executed in the currency. With this information, one can find out how much value belonged to each address at any point in history.

## Installation

1. Make sure [Python 3.6+](https://www.python.org/downloads/) is installed. 
2. Install [pipenv](https://github.com/kennethreitz/pipenv). 

```
$ pip install pipenv 
```

3. Create a _virtual environment_ and specify the Python version to use. 

```
$ pipenv --python=python3.6
```

4. Install requirements.  

```
$ pipenv install 
``` 

5. Run the server:
    * `$ pipenv run python blockchain.py` 
    * `$ pipenv run python blockchain.py -p 8009`
    * `$ pipenv run python blockchain.py --port 8010`
    
```

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.
