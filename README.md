# com_kadi
In following the tradition of using Swahili in terminology. Kadi is both singular and plural for "cards". As this is a simple 'hello world' 
project for the Joomla and Nooku Frameworks, most likely, it will just render swatches on the front end; for quotes, advertisements or HTML5 'aside' simple and brief information snippets.

The Environment of this project is based on the services provided by [Moyo Web Architects](http://moyoweb.nl).

## Requirements

   * Joomla 3.X .
   * Koowa 0.9 or 1.0 (as yet, Koowa 2 is not supported)
   * PHP 5.3.10 or better
   * Moyo Components
       * As of yet, I am not sure which components from the entourage of Moyo Components will be necessary to provide functionality to Kadi.

## Installation

Installation is done through composer. In your `composer.json` file, you should add the following lines to the repositories
section:

```json
{
    "name": "cta/kadi",
    "type": "vcs",
    "url": "https://github.com/white001goat/com_kadi.git"
}
```

The require section should contain the following lines:

```json
    "white001goat/kadi": "0.1.*",
```

Afterward, just run `composer update` from the root of your Joomla project.

### jsymlinker

Another option, currently only available for Moyo developers, is by using the jsymlink script from the [Moyo Git
Tools](https://github.com/derjoachim/moyo-git-tools).


