# Magento 2 Module Webficial Core
<a href="https://webficial.com/" title="Magento Extensions Module" ><img src="https://webficial.com/wp-content/uploads/2021/09/webficial.png" width="100" align="right" title="Magento Adobe Commerce" /></a>

    ``webficial/module-core``

 - [About](#markdown-header-about)
 - [Main Functionalities](#markdown-header-main-functionalities)
 - [Installation](#markdown-header-installation)
 - [Configuration](#markdown-header-configuration)
 - [Specifications](#markdown-header-specifications)
 - [Attributes](#markdown-header-attributes)


## About
- Magento 2 Core Module Extension - This is core module of Webficial Extension Modules.
- We have provide the extrime level of customization of the Adobe Commerce App.


## Main Functionalities
Find Image from the path

## Installation
\* = in production please use the `--keep-generated` option

### Type 1: Zip file

 - Unzip the zip file in `app/code/Webficial`
 - Enable the module by running `php bin/magento module:enable Webficial_Core`
 - Apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer

 - Make the module available in a composer repository for example:
    - private repository `repo.magento.com`
    - public repository `packagist.org`
    - public github repository as vcs
 - Add the composer repository to the configuration by running `composer config repositories.repo.magento.com composer https://repo.magento.com/`
 - Install the module composer by running `composer require webficial/module-core`
 - enable the module by running `php bin/magento module:enable Webficial_Core`
 - apply database updates by running `php bin/magento setup:upgrade`\*
 - Flush the cache by running `php bin/magento cache:flush`

  /*Note : Composer installation allow in some days*/  

## Configuration

### General

## Specifications
- This module is base/core module. This is a generic module.

## Attributes
