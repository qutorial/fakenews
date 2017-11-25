# Fact Chain

Amazing blockchain app to fight the fake news!

Using this blockchain based application it is 
possible to come to a consensus about facts.

News Agencies are the targeted clientele.


## Install

### Hyperledger Playground

This sample can be used in the Hyperledger Composer Playground.

Clone this repository, run zip.sh, import news.bna into the
playground:

https://composer-playground.mybluemix.net/editor


### Local Composer

See the developer guide for Hyperledger Composer and the Makefile.

https://hyperledger.github.io/composer/tutorials/developer-tutorial.html

Install the required Composer development tools. Then:

```
make hard-reset
```

Then you can run a REST server and explore the network:

```
make rest
# if you do not have google-chrome, correct the Makefile to your sensible-browser
make explorer
# to research in the local playground
make playground
```

### The accompanying app

Get the accompanying Angular 2 app and use it with the REST server 
from the previous step.

Clone this app:

https://github.com/qutorial/factchain-ng


then cd into it and run `ng server`.



