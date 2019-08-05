# Project Title

Implementation of RSA public key cryptography featuring OAEP written in Python 3. Includes a command line wrapper for usage via command prompt.

## Getting Started

These instructions will enable you to run the project on your local machine for development/testing.

### Prerequisites

```
Python 3.x
```

### Usage

The cli file for this project features the following arguments:

* new-keys (-n) - bool - whether or not new keys should be generated
* message (-m) - string - message string to be encoded
* coded-message (-c) - location of message string to be decoded
* store-keys (-s) - desired location for saving keys

### Examples

The master branch of this repository features a test essay (approx. 2000 words) that can be used for demonstration. Messages can also be manually input as part of the command.  

For a more lengthy test option, the shakespeare branch includes the complete works of Shakespeare in a .txt document which was encrypted and subsequently decrypted in appoximately a minute total in testing.

## Authors

* **William Strode** - *Implementation* - [strodew](https://github.com/strodew)

## Acknowledgments

 * **James Lee** - Helped with bugfixing and error detection - [jamesl33](https://github.com/jamesl33)
