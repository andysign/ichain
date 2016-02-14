# ichain

ICHAIN, currently on **[ichain.io](http://ichain.io)** is a decentralized solution for storing media images (possibly videos as well). Ichain is designed to work either on a [local](https://ethereum.gitbooks.io/frontier-guide/content/testing_contracts_and_transactions.html) [Ethereum](http://ethereum.org) chain ( see more details  [here](https://souptacular.gitbooks.io/ethereum-tutorials-and-tips-by-hudson/content/private-chain.html) ) or a [public](https://github.com/ethereum/go-ethereum/wiki/geth) [Ethereum](http://ethereum.org) chain. There is also a potential to use ichain with other chains in the future such as the [Bicoin Blockchain](http://bitcoin.org) or the [Namecoin Blockchain](http://namecoin.org/)but for now the focus is on *Ethereum* only.

Due to extremly *high costs* for adding data intro the Blockchain trough [Smart Contracts](http://ethereum.org/greeter) etc, only **hashes** ( **[md5](http://www.freeformatter.com/message-digest.html) hashes** to be more exact ) of images will be saved into the main chain and possibly small thumbnails into the private blockchain. 

## Getting Started

Download the project zip file or use git and install after installing all the prerequisities.

```node index``` or ```nodejs index```



## Prerequisities 

The following are tested

> *nodejs-legacy* v0.10.25; *npm* v1.4.21; *geth* Version: 1.3.3/1.4.0-unstable; 

### Prerequisities Details

* *Node.js* - [Download](http://nodejs.org/) then install, view [nodeschool](http://nodeschool.io/) for more or tutsplus  <br> ```apt-get install nodejs-legacy```
* *Npm* - [Download](https://nodejs.org/en/download/) then install <br> ```apt-get install npm```
* *Go Ethereum* - [Download](http://ethereum.github.io/go-ethereum/) then install or the [compiled binaries](https://github.com/ethereum/go-ethereum/releases/) <br> ```bash <(curl -L https://install-geth.ethereum.org)  ```  

#### Prerequisities Packages 

* TBD

## Authors 

* **Andy B** - [Andysign](http://github.com/andysign)

## License 

This project is not licensed -- the license type is TBD

## Acknowledgments

* Big thanks to H. ;)
