# 1. PhpStorm

<!-- TOC -->

- [1. PhpStorm](#1-phpstorm)
    - [1.1. Settings](#11-settings)
        - [1.1.1. Languages & Frameworks](#111-languages--frameworks)
            - [1.1.1.1. JavaScript](#1111-javascript)
                - [1.1.1.1.1. Setting up Ecmascript](#11111-setting-up-ecmascript)
                - [1.1.1.1.2. Libraries](#11112-libraries)
                - [1.1.1.1.3. Code Quality Tools](#11113-code-quality-tools)
            - [1.1.1.2. PHP](#1112-php)
            - [1.1.1.3. Node.js and NPM](#1113-nodejs-and-npm)
            - [1.1.1.4. Stylesheets](#1114-stylesheets)
                - [1.1.1.4.1. Stylelint](#11141-stylelint)
    - [1.2. Extensions](#12-extensions)

<!-- /TOC -->

## 1.1. Settings

The behavior of PhpStorm can be influenced through a complex GUI. In this section we'll guide you through a few interesting and helpful settings.

### 1.1.1. Languages & Frameworks

#### 1.1.1.1. JavaScript

##### 1.1.1.1.1. Setting up Ecmascript

By default PhPStorm will validate Javascript as Ecmascript 5.1. This will let the IDE run into issues while working with newer version of Ecmascript.

By going into the Languages & Frameworks settings you can find the JavaScript settings. In here you can switch through a simple dropdown to for example the newer Ecmascript 6.

##### 1.1.1.1.2. Libraries

The validating of Javascript can be further extended with additional libraries.

- jQuery
  - Front-end developers working with jQuery can add this library to add jQuery validation to PhpStorm.
- Node.js Core
  - Adds the core library of NodeJS to PhpStorm. This will let the IDE read most of your syntax for validation.
- Express
  - To add specific validation for ExpressJS you will need to add this library on top of the NodeJS core library.

##### 1.1.1.1.3. Code Quality Tools

The vanilla version of PhpStorm comes with the industry standard of validators and linters for Javascript by default. It is required however to enable these *per project*.

#### 1.1.1.2. PHP

At the parent level of the PHP category you can find settings to tell PhpStorm with which version of PHP you're working with. *Version 7.1* or higher is recommended for this setting to let the IDE support you with all the new syntax since previous versions.

#### 1.1.1.3. Node.js and NPM

Next to the Node related settings in the Javascript category, Jetbrains has also provided us with a specific category dedicated to Node.js. When your core library for Node has been setup it may still be required for you to enable the library at this page.

This section also shows an automatically generated list of installed NPM packages, both globally and project specific. It's even possible to install more packages through this GUI, if you don't prefer your terminal of choice.

After clicking on a package you can also choose to upgrade it from within PhpStorm.

#### 1.1.1.4. Stylesheets

##### 1.1.1.4.1. Stylelint

Stylelint can be enabled for PhpStorm through a setting in the category Stylelint under Stylesheets. This will require you to have installed both Node and the Stylelint package. If you have Stylelint and Node installed PhpStorm will usually be able to find both paths. If not, you can manually enter the paths by clicking the *...* button.

## 1.2. Extensions