![img](https://assets.imaginablefutures.com/media/images/ALX_Logo.max-200x150.png)
> RSA Refactoring challenge

<iframe width="560" height="315" src="https://www.youtube.com/embed/tGSUjuSBt1A" title="Mission Impossible theme song (Original)" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## About
This is an optional project.

We have sniffed an unsecured network and found numbers that are used to encrypt very important documents. It seems that those numbers are not always generated using large enough prime numbers. Your mission should you choose to accept it, is to factorize these numbers as fast as possible before the target fixes this bug on their server - so that we can decode the encrypted documents.


## Resources 
1. [RSA](https://en.wikipedia.org/wiki/RSA_(cryptosystem%29))
2. [How does HTTPS provide security](https://stackoverflow.com/questions/3968095/how-does-https-provide-security)
3. [Prime factorization](https://privacycanada.net/mathematics/prime-factorization/)
4. [Why RSA?](https://jaredatandi.hashnode.dev/rsa-factoring)

## Requirements
* [X] You can choose the language of your choice.
* [X] OS needs to be Standard Ubuntu 20.04 LTS/

## Aditional information
### USage
* Usage: ```factors <file>```
    * where <file> is a file containing natural numbers to factor.
    One number per line
    * You can assume that all lines will be valid natural numbers greater than 1
    You can assume that there will be no empy line, and no space before and after the valid number
    * The file will always end with a new line

* Output format:
    * n=p*q
    * one factorization per line
    * p and q don’t have to be prime numbers
    See example

* You can work on the numbers of the file in the order of your choice
* Your program should run without any dependency: You will not be able to install anything on the machine we will run your program on
* Time limit: Your program will be killed after 5 seconds if it hasn’t finish
