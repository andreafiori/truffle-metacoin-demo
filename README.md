# Metacoin

A truffle project downloaded. Some errors have been fixed.
This is a simple implementation with smart contracts written in Solidity.

## Installation

You need to install truffle with NodeJS:

	npm install -g truffle

This will install the framework. Download Ganache as an appx application to add on Windows 10.

You can download and install Drizzle too.

## Running the tests

On Windows you can have an error because it tries to compile the truffle.js file. You must use the truffle.cmd instead:

	truffle.cmd test

On Linux:

	truffle test

## Deploy contracts

To deploy contracts, be sure to configure your client in the truffle.js file and run Ganache or Geth.

Now you are ready to deploy for testing:

	truffle deploy

On Windows

	truffle.cmd deploy

## Truffle commands

	init      Initialize new and empty Ethereum project
	compile   Compile contract source files
	migrate   Run migrations to deploy contracts
	deploy    (alias for migrate)
	build     Execute build pipeline (if configuration present)
	test      Run JavaScript and Solidity tests
	debug     Interactively debug any transaction on the blockchain (experimental)
	opcode    Print the compiled opcodes for a given contract
	console   Run a console with contract abstractions and commands available
	develop   Open a console with a local development blockchain
	create    Helper to create new contracts, migrations and tests
	install   Install a package from the Ethereum Package Registry
	publish   Publish a package to the Ethereum Package Registry
	networks  Show addresses for deployed contracts on each network
	watch     Watch filesystem for changes and rebuild the project automatically
	serve     Serve the build directory on localhost and watch for changes
	exec      Execute a JS module within this Truffle environment
	unbox     Download a Truffle Box, a pre-built Truffle project
	version   Show version number and exit

There is even one additional command:

	truffle develop

## Resources

[Truffle framework](http://truffleframework.com/)
[Solidity](https://solidity.readthedocs.io/)
