# 1. Visual Studio Code

<!-- TOC -->

- [1. Visual Studio Code](#1-visual-studio-code)
    - [1.1. Settings](#11-settings)
    - [1.2. Extensions](#12-extensions)
        - [1.2.1. General](#121-general)
            - [1.2.1.1. Auto Close Tag](#1211-auto-close-tag)
            - [1.2.1.2. Auto Rename Tag](#1212-auto-rename-tag)
            - [1.2.1.3. Better Comments](#1213-better-comments)
            - [1.2.1.4. Code Spell Checker](#1214-code-spell-checker)
            - [1.2.1.5. Material Icon Theme](#1215-material-icon-theme)
        - [1.2.2. Git](#122-git)
            - [1.2.2.1. gitignore](#1221-gitignore)
        - [1.2.3. Markdown](#123-markdown)
            - [1.2.3.1. Auto-Open Markdown](#1231-auto-open-markdown)
            - [1.2.3.2. Markdown TOC](#1232-markdown-toc)
            - [1.2.3.3. Markdownlint](#1233-markdownlint)
        - [1.2.4. PHP](#124-php)
            - [1.2.4.1. PHP Getters & Setters](#1241-php-getters--setters)
        - [1.2.5. NodeJS](#125-nodejs)
            - [1.2.5.1. Heroku-cli](#1251-heroku-cli)
            - [1.2.5.2. html2jade](#1252-html2jade)
            - [1.2.5.3. Pug beautify](#1253-pug-beautify)
            - [1.2.5.4. Puglint](#1254-puglint)
        - [1.2.6. HTML / CSS](#126-html--css)
            - [1.2.6.1. Autoprefixer](#1261-autoprefixer)
            - [1.2.6.2. HTMLHint](#1262-htmlhint)
            - [1.2.6.3. stylelint](#1263-stylelint)

<!-- /TOC -->

## 1.1. Settings

It's easy to enhance Visual Studio Code with quality of life improvements in Visual Studio Code without any extensions to begin with! As the IDE with a JSON-like settings formatting, you can quickly type in your preferences without having to search for them in a standard GUI.

When you start out with the IDE settings, you receive two empty { } brackets. In here, you can simply format settings by going with the "name": "value" format.

Settings use a combination of dots and camelCase to spell out toggles you can set up.

- files.autoSave
  - onFocusChange
- Auto save files on switching between files or windows.
  - onWindowChange
    - Auto save files on switching windows on your operation system.
- editor.minimap.enabled
  - true (default)
  - false
    - Hide the minimap, giving more breathing room for your code
- editor.wordWrap
  - true
    - Wrap words to disable vertical scrolling for better usability.
- emmet.triggerExpansionOnTab
  - true
    - Allows you to use Emmet auto completion in some special situations where it'd be disabled by standard.
- editor.multiCursorModifier
  - alt (default)
    - the standard keybind as seen in PhpStorm.
  - ctrlCmd
    - Changes the keybind to ctrl (Windows) or command (macOS) as seen in Brackets.

## 1.2. Extensions

### 1.2.1. General

General extensions to improve the workflow of Code and add features missing from PhpStorm.

#### 1.2.1.1. Auto Close Tag

Adds the functionality to auto close both HTML and XMl tags while working without Emmett.

#### 1.2.1.2. Auto Rename Tag

Do you remember the times your layout or code broke because you updated the opening tag, but forgot to update the closing tags? With the auto renaming tag you can add this missing functionality from PhpStorm over into Visual Studio Code!

#### 1.2.1.3. Better Comments

By using the Better Comments plugin you can add styles to your comment lines. This can be easily done by annotating, which directly visualizes each comment line to help in managing your code.

#### 1.2.1.4. Code Spell Checker

The Code Spell Checker can add spelling and grammar control to the editor. This extension also works great with camelCase for detecting different words joined together.

By standard, this extension supports English for proofreading your code, to build upon this, the developer has also released child extensions extending the module with other languages.

#### 1.2.1.5. Material Icon Theme

With the Material Icon Theme, you can add stylized icons to not only improve the designs of existing icons, but also add a completely new set for folders. This improves readability and recognizability for the names we use for structuring folders.

This list includes, but is not limited, to lib, images, js, ...

### 1.2.2. Git

#### 1.2.2.1. gitignore

This extension allows you to directly pull premade .gitignore templates from a public library. In the library you can find premades for most languages and libraries, including Wordpress, Drupal, Node and many more!

### 1.2.3. Markdown

#### 1.2.3.1. Auto-Open Markdown

In our programming classes our teachers always emphasize that "a good developer is a lazy one". With this extension, you can save one additional click while working on Markdown files by auto opening the preview on the side in Visual Studio Code.

#### 1.2.3.2. Markdown TOC

To add more structure to .md files you can use this table of contents extension. Quickly add and update sections in templates and automatically add an interactive table of contents.

#### 1.2.3.3. Markdownlint

Another linter to assist you with writing stronger quality of code. This linter will output problems with the markdown to the problems tab view in the Terminal of Visual Studio Code.

In most cases you can automatically fix issues and read learn more about the guidelines through included links.

### 1.2.4. PHP

#### 1.2.4.1. PHP Getters & Setters

Kickstart your OOP programming in PHP by instantly generating your getters and setters for your classes. Be advised to use this extension after learning the basics from OOP and Getters & Setters so you can write and understand the code yourself.

### 1.2.5. NodeJS

Pug is the HTML render standard for ExpressJS. With the following extensions you can increase your workflow with writing your template files.

#### 1.2.5.1. Heroku-cli

Quickly get your logs and check the status of online Heroku apps without leaving the editor. After installing the Heroku CLI to the OS of your choice, it will be possible to run heroku commands from the included terminal in Visual Studio Code.

#### 1.2.5.2. html2jade

You might be aware of the online html2jade tool to instantly convert your HTML markup into Pug. However, you can take it to the next step by installing this plugin, allowing you to directly convert Html to Pug from within the editor.

#### 1.2.5.3. Pug beautify

Pug beautify allows you to clean up your Pug and automatically format resulting in cleaner codes.

#### 1.2.5.4. Puglint

To help understanding pug and producing better coding standards, puglint will help you with writing qualitative Pug templates.

### 1.2.6. HTML / CSS

#### 1.2.6.1. Autoprefixer

Tired of manually checking for browser backwards compatibility? Or do you want to ensure you're not forgetting any special prefixes in your CSS markup? Go and give the autoprefixer module a try!

By opening the Code's built in command prompt you'll be able to use a flexible ui to automatically insert your prefixes. This extensions also works well in combination with Mixins.

#### 1.2.6.2. HTMLHint

HTMLHint is an interesting extension to help as well with the quality of your code. This time your HTML markup shall be validated for various quality checks.

This extension uses the NPM package with the same name. This can be either a locally installed package for the project or a global installation. If neither are found, an embedded version to the extension will be used.

#### 1.2.6.3. stylelint

Validate your CSS markup on the go while coding. Automatically output problems and hints to improve quality to the panel of Visual Studio Code.