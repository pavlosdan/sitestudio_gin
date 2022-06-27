# Site Studio Gin
Integrates Acquia Site Studio with the Gin admin theme.

## Installation

To use this module, you must already have a Drupal site, Gin as your admin theme and Acquia Site Studio.

Add the following to the `repositories` section of your project's composer.json:

```
"sitestudio_gin": {
    "type": "vcs",
    "url": "https://github.com/pavlosdan/sitestudio_gin.git"
}
```

or run:

```
composer config repositories.sitestudio_gin vcs https://github.com/pavlosdan/sitestudio_gin.git
```

Require the module with Composer:

`composer require acquia/sitestudio_gin`

## Usage
- Install module as usual.
- Once enabled module should just work.
