# SmartAgoraDocumentation

Welcome to the Smartagora documentation.

## Support

For any question please contact us: mail@smart-agora.org

## Website

https://smart-agora.org/

## License

The project is licensed under the GPL-2.0 license.

## Publications

Evangelos Pournaras - Proof of Witness Presence: Blockchain Consensus for Augmented Democracy in Smart Cities 
https://arxiv.org/abs/1907.00498

## References

### DIAS

A documentation of DIAS can be found here https://github.com/epournaras/DIAS-Documentation.


## Read the Docs

This repository contains the documentation for the Smartagora project.

The documentation is written in markup language called **reStructuredText**, often abbreviated as **reST**.

The link to Getting Started page can be found [here](https://docs.readthedocs.io/en/latest/getting_started.html).

The link to the syntax of writing in **reST** can be found [here](http://www.sphinx-doc.org/en/master/usage/restructuredtext/basics.html).

Why should we even use this and not Markdown language? [here](http://ericholscher.com/blog/2016/mar/15/dont-use-markdown-for-technical-docs/).

A 20-minutes video tutorial can be found [here](https://www.youtube.com/watch?v=oJsUvBQyHBs&feature=youtu.be).

### PREREQUISITES

`Sphinx` is a Python-based tool for generating this kind of documentation. Therefore, take the following steps:

1. Install python if it is not already installed on your machine. Ubuntu 16.04 comes with both python 2 and python 3 already.

2. Install `Sphinx` by typing this in your terminal:

```
sudo pip3 install sphinx sphinx-autobuild
```

3. Create a directory `docs` within your project, and enter this directory

4. `Sphinx` must be configured now. The following command will start the configuration process that is self-explanatory, with many defaults already set.

    There are two important settings to be followed:

    - Separate source and build directories (y/n) [n]: y

    - Note that you should accept automatic creation of make files since it will save you a lot of time.
