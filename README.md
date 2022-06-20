# dapp for minting trainee certificates.

This dapp will illustrate how best 10 academy can leverage the algorand blockchain to mint learner certificates.

## Usage

The file `auction/operations.py` provides a set of functions that can be used to create and interact
with auctions. See that file for documentation.

## Development Setup

This repo requires Python 3.6 or higher. We recommend you use a Python virtual environment to install
the required dependencies.

Set up venv (one time):
 * `python3 -m venv venv`

Active venv:
 * `. venv/bin/activate` 


Install dependencies:
* `pip install -r requirements.txt`

Run tests:
* First, start an instance of [sandbox](https://github.com/algorand/sandbox) (requires Docker): `./sandbox up nightly`
* `pytest`
* When finished, the sandbox can be stopped with `./sandbox down`


