<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Sphinx for YunoHost

[![Integration level](https://dash.yunohost.org/integration/sphinx.svg)](https://dash.yunohost.org/appci/app/sphinx) ![](https://ci-apps.yunohost.org/ci/badges/sphinx.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/sphinx.maintain.svg)  
[![Install Sphinx with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sphinx)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Sphinx quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Sphinx is a tool that makes it easy to create intelligent and beautiful documentation, written by Georg Brandl and licensed under the BSD license.

It was originally created for the Python documentation, and it has excellent facilities for the documentation of software projects in a range of languages. Of course, this site is also created from reStructuredText sources using Sphinx! The following features should be highlighted:

### Features

- Output formats: HTML (including Windows HTML Help), LaTeX (for printable PDF versions), ePub, Texinfo, manual pages, plain text
- Extensive cross-references: semantic markup and automatic links for functions, classes, citations, glossary terms and similar pieces of information
- Hierarchical structure: easy definition of a document tree, with automatic links to siblings, parents and children
- Automatic indices: general index as well as a language-specific module indices
- Code handling: automatic highlighting using the Pygments highlighter
- Extensions: automatic testing of code snippets, inclusion of docstrings from Python modules (API docs), and more
- Contributed extensions: dozens of extensions contributed by users; most of them installable from PyPI


**Shipped version:** 4.4.0~ynh1



## Screenshots

![](./doc/screenshots/example.jpg)

## Disclaimers / important information

* Any known limitations, constrains or stuff not working, such as (but not limited to):
    * requiring a full dedicated domain ?
    * architectures not supported ?
    * not-working single-sign on or LDAP integration ?
    * the app requires an important amount of RAM / disk / .. to install or to work properly
    * etc...

* Other infos that people should be aware of, such as:
    * any specific step to perform after installing (such as manually finishing the install, specific admin credentials, ...)
    * how to configure / administrate the application if it ain't obvious
    * upgrade process / specificities / things to be aware of ?
    * security considerations ?

## Documentation and resources

* Official app website: https://www.sphinx-doc.org
* Official admin documentation: https://www.sphinx-doc.org/en/master/contents.html
* Upstream app code repository: https://github.com/sphinx-doc/sphinx
* YunoHost documentation for this app: https://yunohost.org/app_sphinx
* Report a bug: https://github.com/YunoHost-Apps/sphinx_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/sphinx_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/sphinx_ynh/tree/testing --debug
or
sudo yunohost app upgrade sphinx -u https://github.com/YunoHost-Apps/sphinx_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps