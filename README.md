[![Shopigo](https://www.shopigo.ch/wp-content/uploads/2018/08/github-shopigo-logo.png)](https://www.shopigo.ch)

# Magento 2 Price Format extension by [Shopigo](https://www.shopigo.ch)

This extension adds a feature which allow to configure the display format of prices and subtotals.

Price display settings (thousand separator, decimal separator, symbol position) can be configured per currency and per store.

![](https://www.shopigo.ch/wp-content/uploads/2018/09/github-extension-price-format-settings.jpg)

Example:

![](https://www.shopigo.ch/wp-content/uploads/2018/09/github-extension-price-format-display.jpg)

## Requirements

Magento Open Source Edition 2.2.x.

## Installation

## Method 1 - Installing via composer

- Switch to your Magento project root
- Run `composer require shopigo/magento2-extension-price-format`

## Method 2 - Installing using archive

- Download [ZIP Archive](https://github.com/shopigo/magento2-extension-price-format/archive/master.zip)
- Switch to your Magento project root
- Create folder `app/code/Shopigo/PriceFormat`
- Extract zip into path

### Enable extension

- Switch to your Magento project root
- Run the following commands to enable the module and clear static contents generated by Magento:
```
php bin/magento module:enable Shopigo_PriceFormat
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
```

## How to use it

- Log into your Magento back-office
- Go to the menu "Stores > Configuration > Shopigo Extensions > Price Format"
- Configure your formats in the field "Price Format"
- Set the parameter "Enabled" to "Yes"
- Flush Magento caches from the menu "System > Tools > Cache Management"

Note: to customize currency symbols, go to the menu "Stores > Currency > Currency Symbols".

## Support

If you have any issues, open a bug report in GitHub's [issue tracker](https://github.com/shopigo/magento2-extension-price-format/issues).

## Need more features?

Please contact us to get a quote https://www.shopigo.ch/contact

## Change logs

**Version 1.0.1** (2010-10-09)
- Fix composer.json for Magento 2.2.0-2.2.5

**Version 1.0.0** (2018-09-04)
- First version

## License

The code is licensed under [Open Software License ("OSL") v. 3.0](http://opensource.org/licenses/osl-3.0.php).

<br/>Enjoy!<br/>
[Shopigo](https://www.shopigo.ch)