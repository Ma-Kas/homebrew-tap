# Homebrew Tap

This repository holds formulae that can be installed with [brew](https://brew.sh).

## How To

To install a program you first need to `brew
tap` this repository to get the formulae. See [tap](https://docs.brew.sh/brew-tap.html) docs for more on `brew tap`.

Open a terminal and run the following `brew` command:

```sh
brew tap Ma-Kas/tap
```

This command will clone the repository to your computer and make the
formulae availabe. You can then install each program with brew, e.g.

```sh
brew install paymostats
```
to install [paymostats](https://github.com/Ma-Kas/paymostats).

For updates, simply run
```sh
brew upgrade paymostats
```

## Feedback

Feel free to leave an issue in this repository related to brew issues. 
For software related issues see the projects repository. To find a
project repository run `brew info`, for example with `paymostats`

```sh
$ brew info paymostats
```
