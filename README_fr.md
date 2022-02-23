# Sphinx pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/sphinx.svg)](https://dash.yunohost.org/appci/app/sphinx) ![](https://ci-apps.yunohost.org/ci/badges/sphinx.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/sphinx.maintain.svg)  
[![Installer Sphinx avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=sphinx)

*[Read this readme in english.](./README.md)*
*[Lire ce readme en français.](./README_fr.md)*

> *Ce package vous permet d'installer Sphinx rapidement et simplement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, regardez [ici](https://yunohost.org/#/install) pour savoir comment l'installer et en profiter.*

## Vue d'ensemble

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


**Version incluse :** 4.4.0~ynh1



## Captures d'écran

![](./doc/screenshots/example.jpg)

## Avertissements / informations importantes

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

## Documentations et ressources

* Site officiel de l'app : https://www.sphinx-doc.org
* Documentation officielle de l'admin : https://www.sphinx-doc.org/en/master/contents.html
* Dépôt de code officiel de l'app : https://github.com/sphinx-doc/sphinx
* Documentation YunoHost pour cette app : https://yunohost.org/app_sphinx
* Signaler un bug : https://github.com/YunoHost-Apps/sphinx_ynh/issues

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/sphinx_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/sphinx_ynh/tree/testing --debug
ou
sudo yunohost app upgrade sphinx -u https://github.com/YunoHost-Apps/sphinx_ynh/tree/testing --debug
```

**Plus d'infos sur le packaging d'applications :** https://yunohost.org/packaging_apps