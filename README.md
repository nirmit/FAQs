# FAQ Plugin for CakePHP #

for cake 2.x

The FAQ plugin so I won't have to code a FAQ again

## Installation ##

_[GIT Submodule]_

In your app directory type:

```shell
git submodule add -b master git://github.com/luksm/CakePHP-Plugin-FAQ.git Plugin/FAQ
git submodule init
git submodule update
```

_[GIT Clone]_

In your `Plugin` directory type:

```shell
git clone -b master git://github.com/luksm/CakePHP-Plugin-FAQ.git FAQ
```

The plugin is pretty easy to set up, all you need to do is to copy it to you application plugins folder and load the needed tables. You can create database tables using the schema shell:

	./Console/cake schema create users --plugin FAQ

## Requirements ##

* PHP version: PHP 5.2+
* CakePHP version: Cakephp 2.0

## TO-DOs ##

* [ ] List Features

## Support ##

For support and feature request, please create an issue

## Branch strategy ##

The master branch holds the STABLE latest version of the plugin.
Develop branch is UNSTABLE and used to test new features before releasing them.

All versions are updated with security patches.

## Contributing to this Plugin ##

Please feel free to contribute to the plugin with new issues, requests, unit tests and code fixes or new features. If you want to contribute some code, create a feature branch from develop, and send us your pull request. Unit tests for new features and issues detected are mandatory to keep quality high.

## License ##

Copyright 2014, [Lucas Machado](http://lucasms.net)

Licensed under [The MIT License](http://www.opensource.org/licenses/mit-license.php)<br/>
Redistributions of files must retain the above copyright notice.
