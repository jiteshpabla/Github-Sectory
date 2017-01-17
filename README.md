# Github Sectory

[![Build Status](https://travis-ci.org/amarlearning/Github-Sectory.svg?branch=master)](https://travis-ci.org/amarlearning/Github-Sectory/)
[![MIT LICENSE](https://img.shields.io/pypi/l/pyzipcode-cli.svg)](http://amarlearning.mit-license.org/)
[![Issues](https://camo.githubusercontent.com/926d8ca67df15de5bd1abac234c0603d94f66c00/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636f6e747269627574696f6e732d77656c636f6d652d627269676874677265656e2e7376673f7374796c653d666c6174)](https://github.com/amarlearning/Github-Sectory/issues)

> CLI for downloading sub-directory of any Github repository!

## Demo
![Demo GitHub Sectory](https://raw.githubusercontent.com/amarlearning/Github-Sectory/master/extras/sreencast.gif)

## Install
```
$ git clone https://github.com/amarlearning/Github-Sectory.git
$ cd Github-Sectory && pip install -r requirements.txt
```
## Usage

### Commands available
```
$ python main.py <link_to_repo_directory>

Example:
  $ python main.py https://github.com/amarlearning/PyStalker/tree/master/version01

```

> **OR**

```

$ python main.py <github_username> -r <repository name> -d <directory name> [arguments]

Needed:
  -r, -d for repository and directory

Optional:
  -b for branch                              [boolean]
 
Examples:
  $ python main.py GoogleChrome -r samples -d push-messaging-and-notifications 
  $ python main.py GoogleChrome -r samples -d push-messaging-and-notifications -b gh-pages
 
```
**Note:** Default branch will be master

***

## Issues

You can report the bugs at the [issue tracker](https://github.com/amarlearning/Github-Sectory/issues)

**OR**

You can [tweet me](https://twitter.com/iamarpandey) if you can't get it to work. In fact, you should tweet me anyway.

***

##License

Built with ♥ by Amar Prakash Pandey([@amarlearning](http://github.com/amarlearning)) under [MIT License](http://amarlearning.mit-license.org/) 

You can find a copy of the License at http://amarlearning.mit-license.org/
