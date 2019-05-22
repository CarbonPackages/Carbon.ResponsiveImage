[![Latest Stable Version](https://poser.pugx.org/carbon/responsiveimage/v/stable)](https://packagist.org/packages/carbon/responsiveimage)
[![Total Downloads](https://poser.pugx.org/carbon/responsiveimage/downloads)](https://packagist.org/packages/carbon/responsiveimage)
[![License](https://poser.pugx.org/carbon/responsiveimage/license)](https://packagist.org/packages/carbon/responsiveimage)
[![GitHub forks](https://img.shields.io/github/forks/CarbonPackages/Carbon.ResponsiveImage.svg?style=social&label=Fork)](https://github.com/CarbonPackages/Carbon.ResponsiveImage/fork)
[![GitHub stars](https://img.shields.io/github/stars/CarbonPackages/Carbon.ResponsiveImage.svg?style=social&label=Stars)](https://github.com/CarbonPackages/Carbon.ResponsiveImage/stargazers)
[![GitHub watchers](https://img.shields.io/github/watchers/CarbonPackages/Carbon.ResponsiveImage.svg?style=social&label=Watch)](https://github.com/CarbonPackages/Carbon.ResponsiveImage/subscription)

# Carbon.ResponsiveImage Package for Neos CMS

This is basically a wrapper for [Sitegeist.Lazybones](https://github.com/sitegeist/Sitegeist.Lazybones). You'll get two Components: [`Carbon.ResponsiveImage:Tag`](Resources/Private/Fusion/Component/Tag.fusion) and [`Carbon.ResponsiveImage:Background`](Resources/Private/Fusion/Component/Tag.fusion)

## Installation

Most of the time you have to make small adjustments to a package (e.g. configuration in `Settings.yaml`). Because of that, it is important to add the corresponding package to the composer from your theme package. Mostly this is the site packages located under `Packages/Sites/`. To install it correctly go to your theme package (e.g.`Packages/Sites/Foo.Bar`) and run following command:

```bash
composer require carbon/responsiveimage --no-update
```

The `--no-update` command prevent the automatic update of the dependencies. After the package was added to your theme `composer.json`, go back to the root of the Neos installation and run `composer update`. Et voilà! Your desired package is now installed correctly.
