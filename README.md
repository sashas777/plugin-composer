# Composer-Plugin for [CaptainHook](https://github.com/sebastianfeldmann/captainhook)

This is a composer-plugin that installs CaptainHook. For more information visit it's Website.

## Installation:

As this is a composer-plugin the prefered method is to use composer for installation.
 
```bash
$ composer require captainhook/plugin-composer`
```

Everything else will happen automagically.

## Setup

The plugin will install CaptaionHook and make sure the git-hoks are installed. The configuration though is still 
done using CaptainHook.

So after first installation you should run `vendor/bin/captainhook  configure -e` and then commit the file 
`captainhook.json` to version control. Then everyone using your project will also have the configured hooks installed.

## A word of warning

It is still possible to commit without invoking the hooks. 
So make sure you run appropriate backend-sanity checks on 
your code!