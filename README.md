# Kirby Autobuster Plugin

This plugin is based on the original Cachebuster by Bastian Allgeier, the modified version by Lukas Kleinschmidt with further modifications & enhancemnets by Sonja Broda & James Steel.

Original plugin did not cache bust autoloaded Javascript or CSS. This plugin does.

## Commerical Usage

This plugin is free but if you use it in a commercial project please consider to
- [make a donation 🍻](https://paypal.me/hashandsalt?locale.x=en_GB) or
- [buy a Kirby license using this affiliate link](https://a.paddle.com/v2/click/1129/36141?link=1170)

## Features

* No longer requires modifications to server configuration files
* Will cache bust auto loaded CSS & JavaScript

## Requirements

This plugin requires Kirby 2.4+

## Installation

To use this plugin, place all the files in `site/plugins/autobuster`.

Now you can activate the plugin with following line in your `config.php`.

```
c::set('autobuster', true);
```

## Authors

Bastian Allgeier, Lukas Bestle, Lukas Kleinschmidt, Sonja Broda & James Steel
