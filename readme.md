# Classification Tree for Pimcore 5
[![Build Status](https://travis-ci.org/DivanteLtd/pimcore-classification-tree.svg?branch=master)](https://travis-ci.org/DivanteLtd/pimcore-classification-tree)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/867f5904381d4e3a86bf33f2b5a99401)](https://www.codacy.com/app/Divante/pimcore-classification-tree?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=DivanteLtd/pimcore-classification-tree&amp;utm_campaign=Badge_Grade)
[![Latest Stable Version](https://poser.pugx.org/divante-ltd/pimcore-classification-tree/v/stable)](https://packagist.org/packages/divante-ltd/pimcore-classification-tree)
[![Total Downloads](https://poser.pugx.org/divante-ltd/pimcore-classification-tree/downloads)](https://packagist.org/packages/divante-ltd/pimcore-classification-tree)
[![License](https://poser.pugx.org/divante-ltd/pimcore-classification-tree/license)](https://github.com/DivanteLtd/pimcore-classification-tree/blob/master/LICENSE)

Classification Tree lets you add new custom view with classification tree.

![Classification Tree](docs/example.jpeg?raw=true "Classification Tree")

**Table of Contents**
- [Classification Tree](#classification-tree)
	- [Compatibility](#compatibility)
	- [Installing/Getting started](#installinggetting-started)
	- [Requirements](#requirements)
	- [Configuration](#configuration)
	- [Testing](#testing)
	- [Contributing](#contributing)
	- [Licence](#licence)
	- [Standards & Code Quality](#standards--code-quality)
	- [About Authors](#about-authors)

## Compatibility
This module is compatible with Pimcore 5.3.0 and higher.

## Installing/Getting started

```bash
composer require divante-ltd/pimcore-classification-tree
```

Enable the Bundle:
```bash
./bin/console pimcore:bundle:enable DivanteClassificationTreeBundle
```

## Requirements
This plugin requires existence of classes: Product

## Configuration
In Pimcore panel select Extensions click Install and Enable.

## Testing
Unit Tests:
```bash
PIMCORE_TEST_DB_DSN="mysql://username:password@localhost/pimcore_test" \
    vendor/bin/phpunit
```

Functional Tests:
```bash
PIMCORE_TEST_DB_DSN="mysql://username:password@localhost/pimcore_test" \
    vendor/bin/codecept run -c tests/codeception.dist.yml
```

## Contributing
If you'd like to contribute, please fork the repository and use a feature branch. Pull requests are warmly welcome.

## Licence 
CoreShop VsBridge source code is completely free and released under the 
[GNU General Public License v3.0](https://github.com/DivanteLtd/pimcore-classification-tree/blob/master/LICENSE).

## Standards & Code Quality
This module respects all Pimcore 5 code quality rules and our own PHPCS and PHPMD rulesets.

## About Authors
![Divante-logo](http://divante.co/logo-HG.png "Divante")

We are a Software House from Europe, existing from 2008 and employing about 150 people. Our core competencies are built 
around Magento, Pimcore and bespoke software projects (we love Symfony3, Node.js, Angular, React, Vue.js). 
We specialize in sophisticated integration projects trying to connect hardcore IT with good product design and UX.

We work for Clients like INTERSPORT, ING, Odlo, Onderdelenwinkel and CDP, the company that produced The Witcher game. 
We develop two projects: [Open Loyalty](http://www.openloyalty.io/ "Open Loyalty") - an open source loyalty program 
and [Vue.js Storefront](https://github.com/DivanteLtd/vue-storefront "Vue.js Storefront").

We are part of the OEX Group which is listed on the Warsaw Stock Exchange. Our annual revenue has been growing at a 
minimum of about 30% year on year.

Visit our website [Divante.co](https://divante.co/ "Divante.co") for more information.
