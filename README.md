# suncalc

<!-- This file was generated by https://github.com/ypid/suncalc/blob/master/scripts/template. Do not edit this file directly but
     instead have a look at: ./metainfo.json, ./templates/ports_README.md.j2 at https://github.com/ypid/suncalc. -->

[![Build Status](https://travis-ci.org/ypid/suncalc.svg?branch=master)](https://travis-ci.org/ypid/suncalc)
[![BSD licensed](https://img.shields.io/badge/license-BSD-blue.svg)](https://tldrlegal.com/license/bsd-2-clause-license-%28freebsd%29)
[![haxelib version](https://img.shields.io/badge/Haxe-v1.7.0-blue.svg)](http://lib.haxe.org/p/suncalc)
[![NPM version](https://img.shields.io/npm/v/suncalc.svg)](https://www.npmjs.org/package/suncalc)
[![Packagist version](https://img.shields.io/packagist/v/ypid/suncalc.svg)](https://packagist.org/packages/ypid/suncalc)


The SunCalc module allows to calculate sun position,
sunlight phases (times for sunrise, sunset, dusk, etc.),
moon position and lunar phase for the given location and time.

The library was ported to Haxe by [Robin `ypid` Schneider](https://github.com/ypid) to allow using it in a library for [opening hours](https://github.com/opening-hours/opening_hours.js/issues/136).

It is based on the [JavaScript implementation](https://github.com/mourner/suncalc)
created by [Vladimir Agafonkin](http://agafonkin.com/en) ([@mourner](https://github.com/mourner))
as a part of the [SunCalc.net project](http://suncalc.net).

Most calculations are based on the formulas given in the excellent Astronomy Answers articles
about [position of the sun](http://aa.quae.nl/en/reken/zonpositie.html)
and [the planets](http://aa.quae.nl/en/reken/hemelpositie.html).
You can read about different twilight phases calculated by SunCalc
in the [Twilight article on Wikipedia](https://en.wikipedia.org/wiki/Twilight).

Refer to the [API documentation](https://ypid.github.io/suncalc/suncalc/SunCalc.html) for details.

## Install

Install the library for your favorite language by executing one of the following commands:

```Shell
haxelib install suncalc         # Haxe
npm install suncalc             # JavaScript/Node.JS
composer require ypid/suncalc   # PHP
```

## Internals
This library was automatically build using [Haxe](http://haxe.org/) to target PHP.

Refer to https://github.com/ypid/suncalc when you want to contribute. Note that you should only report issues against [this repository](https://github.com/ypid/suncalc-php) when you think the issue only occurs in the PHP port of this library. If you are unsure, report [against the source repository](https://github.com/ypid/suncalc) instead.

## License

[BSD-2-Clause](https://tldrlegal.com/license/bsd-2-clause-license-%28freebsd%29)
