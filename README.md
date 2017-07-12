# entbox token contract

## prerequisites
- [read an introduction to ethereum contracts](https://medium.com/@ConsenSys/a-101-noob-intro-to-programming-smart-contracts-on-ethereum-695d15c1dab4)
- solc: http://solidity.readthedocs.io/en/develop/installing-solidity.html
- python: https://www.python.org/downloads/
- pip: https://pip.pypa.io/en/stable/installing/
- virtualenv: http://docs.python-guide.org/en/latest/dev/virtualenvs/
- testrpc: https://github.com/pipermerriam/eth-testrpc
- truffle: https://github.com/trufflesuite/truffle

## run contract tests
### start test ethereum client 
````
testrpc --port 8444
````
### compile and deploy contract to testrpc
```
truffle compile
truffle deploy
```
you need to redeploy everytime after you restarted testrpc!

### run tests
```
truffle test
```




