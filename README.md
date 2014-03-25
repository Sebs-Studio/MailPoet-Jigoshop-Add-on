# MailPoet Jigoshop Add-on

Contributors: wysija, sebd86
Tags: mailpoet, wysija, jigoshop, sebs studio, extension, add-on
Requires at least: 3.7.1
Tested up to: 3.8.1
Stable tag: trunk
License: GPLv2 or later
License URI: http://www.gnu.org/licenses/gpl-2.0.html

## Description

This simple plugin adds a checkbox on checkout page for your customers to subscribe to your MailPoet newsletters.

## Localization
* English (US)[Default] - always included. mailpoet_jigoshop_add_on.pot file in language folder for translations.
* English (UK)
* Turkish (TR) by muratenez
* Armenian (HY) by haykojanjado

If you would like to do a translation for the plugin, you can do so via Transifex.  (https://www.transifex.com/projects/p/mailpoet-jigoshop-add-on/)

Simply select or add a language you want to translate in and I will attach the language in the next version release. You will need an account on Transifex to do this.

If you have done a translation via PoEdit, then you are welcome to send that also. To send your translation files contact me. (http://www.sebs-studio.com/contact/?contacting=Translations)

I'll acknowledge your contribution here with either your full name or username given.

## Documentation

For all documentation on this plugin go to: http://docs.sebs-studio.com/user-guide/extension/mailpoet-jigoshop-add-on/

## Contributing

To contribute to the plugin, visit https://github.com/seb86/MailPoet-Jigoshop-Add-On/blob/master/CONTRIBUTING.md for details.

## Installation

__Minimum Requirements__

* MailPoet http://wordpress.org/plugins/wysija-newsletters/
* Jigoshop http://wordpress.org/plugins/jigoshop/

__Automatic installation__

Automatic installation is the easiest option as WordPress handles the file transfers itself and you don't even need to leave your web browser. To do an automatic install of MailPoet Jigoshop Add-On, log in to your WordPress admin panel, navigate to the Plugins menu and click Add New.

In the search field type "MailPoet Jigoshop Add-On" and click Search Plugins. Once you've found my plugin extension you can view details about it such as the the point release, rating and description. Most importantly of course, you can install it by simply clicking Install Now. After clicking that link you will be asked if you're sure you want to install the plugin. Click yes and WordPress will automatically complete the installation.

__Manual installation__

The manual installation method involves downloading my plugin and uploading it to your webserver via your favourite FTP application.

1. Download the plugin file to your computer and unzip it
2. Using an FTP program, or your hosting control panel, upload the unzipped plugin folder to your WordPress installation's wp-content/plugins/ directory.
3. Activate the plugin from the Plugins menu within the WordPress admin.

## Setting up the Plugin

Simply config this plugin under Jigoshop settings in the MailPoet tab.

Enable the checkbox field to show on the checkout page. You can also change the label of the checkbox. Default 'Yes, add me to your mailing list'

Next is the 'Newsletters', they are listed on a sub-page under Jigoshop called 'MailPoet Lists'.

Each list you created in MailPoet that you have enabled to send to is listed here. Simply tick the checkbox next to the Newsletter list your customers will be subscribed to and press 'Save Settings'.

That's it, now when your customers tick the subscribe button on the checkout page, they will be subscribed to the newsletters you selected when processing an order.

## Upgrading

Automatic updates should work like a charm; as always though, ensure you backup your site just in case.

## Screenshots

1. Subscribe checkbox field on checkout page.
2. Jigoshop MailPoet Checkout Settings.
3. Jigoshop MailPoet Newsletters Enabled.

## Changelog

__1.0.4 - 25/03/2014__

* ADDED - More languages, Arabic, Greek, Portuguese (Brazil), Russian
* CORRECTED - If function 'mailpoet_lists' is already defined, then don't load again.
* REMOVED - Translation of the brand name 'MailPoet' only.
* UPDATED - POT file

__1.0.3 - 07/01/2014__

* Renamed - 'lang' folder to 'languages'.
* Added - mailpoet-jigoshop-addon.pot file.
* Updated - Read me file.

__1.0.2 - 06/01/2014__

* Added - Armenian language by haykojanjado
* Corrected - Default source language from en_GB to en_US, now both UK and US language is available.

__1.0.1 - 04/01/2014__

* Added - Turkish language by muratenez

__1.0.0 - 20/12/2013__

* Initial Release.