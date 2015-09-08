# Neos CMS Twitter Bootstrap Plugin

The Weissheiten Bootstrap package should allow its users to get an easy introduction to Neos CMS with the popular bootstrap template. Starting from the great TYPO3.NeosDemoTypo3Org Site package the amount of available content elements has been significantly extended and at some places altered.
A big thank you to the awesome Neos CMS core team that gave me insight needed to create many of these new nodes.  

## Installation

Add this repository to your composer.json:

```
    {
        "type": "git",
        "url": "https://github.com/egobude/Weissheiten.Neos.Bootstrap.git"
    }
```

And add this to require:

```
"weissheiten/neos-bootstrap": "2.*"
```

And the run this command to fetch the plugin:

```
composer update
```

## Including Bootstrap

The Weissheiten Bootstrap package does NOT use the TYPO3.Twitter.Bootstrap package at the moment.
So you have to include either that package or Bootstrap itself yourself in your main templates.

## Author

* email: florian.weiss@weissheiten.at 
* url: http://www.weissheiten.at 
* twitter: @WeissheitenWien