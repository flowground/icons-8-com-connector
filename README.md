# ![LOGO](logo.png) Use a [New Version](https://icons8.github.io/icons8-docs/) Instead **flow**ground Connector

## Description

A generated **flow**ground connector for the Use a [New Version](https://icons8.github.io/icons8-docs/) Instead API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/icons8.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:42:21+03:00

## API Description

# Icons8 API

Icons8 API allows us to search and obtain [our icons](https://icons8.com/web-app).

You're welcome to use our icons to extend the functionality of your web and mobile applications, website templates, and even tattoos.

![Tattoos](https://cdn.rawgit.com/icons8/api-docs/cff6fdf0/tattoos.svg)

## Usage Examples

Some examples of what you can do with our icons:

* **Template customization.** This way, [Canva](https://www.canva.com/) uses our icons to customize their layouts.

* **Graphics and text editors.** [Gravit](https://gravit.io/) allows to insert our icons into the mockups.

* **Any application with customization.** [TimeTune](http://timetune.center/) uses our icons to customize the activities.

## Getting Started

To get started, please [contact us](https://icons8.com/contact) to obtain an API key.

## Pricing

Our API license starts at $100/month.

## Authorization

This API does not require authorization.

## Actions

### Categories

> The operation will not return the categories that have less than 10 icons.<br/>
> We need it to test the categories without showing garbage on the production website.

#### Input Parameters
* `platform` - _required_ - the platform that we are searching icons for
    Possible values: ios7, win8, win10, android, androidL, color, office.
* `language` - _required_ - the language code to get localized result
    Possible values: en-US, fr-FR, de-DE, it-IT, pt-BR, pl-PL, ru-RU, es-ES.

### By Category

#### Input Parameters
* `category` - _required_ - the code of category
* `subcategory` - _required_ - the code of subcategory
* `amount` - _required_ - the maximum number of icons which you'd like to receive
* `offset` - _required_ - the offset from the first received result
* `platform` - _required_ - the style of the icons
    Possible values: ios7, win8, win10, android, androidL, color, office.
* `language` - _required_ - the language code to get localized result
    Possible values: en-US, fr-FR, de-DE, it-IT, pt-BR, pl-PL, ru-RU, es-ES.

### Latest

#### Input Parameters
* `amount` - _required_ - the maximum number of icons which you'd like to receive
* `offset` - _required_ - the offset from the first received result
* `platform` - _required_ - the style of the icons
    Possible values: ios7, win8, win10, android, androidL, color, office.
* `language` - _required_ - the language code to get localized result
    Possible values: en-US, fr-FR, de-DE, it-IT, pt-BR, pl-PL, ru-RU, es-ES.
* `term` - _required_

### By Keyword v3

#### Input Parameters
* `term` - _required_ - the name or tag of the icon or any other phrase.
e.g. use "@home" to find icons with the tag "home" and "=home" to find icons with the name "home"

* `amount` - _required_ - the maximum number of icons which you'd like to receive (will be multiplied by platforms count, if you didn't specify the platform and didn't set the 'exact_amount' parameter)
* `exact_amount` - _required_ - set it to 'true' if you'd like to receive the exact amount of icons, not multiplied by platforms count
* `offset` - _required_ - the offset from the first received result
* `platform` - _required_ - the style of the icons
    Possible values: ios7, win8, win10, android, androidL, color, office.
* `language` - _required_ - the language code to get localized result
    Possible values: en-US, fr-FR, de-DE, it-IT, pt-BR, pl-PL, ru-RU, es-ES.

### Totals

#### Input Parameters
* `since` - _required_ - the optional date to calculate the total number of icons that were created after it.
It should be in format "four year digits - dash - two month number digits - dash - two day number digits. For example 2014-12-31 means "31th of December, 2014".


### By Keyword v4

#### Input Parameters
* `term` - _required_ - the name or tag of the icon or any other phrase.
e.g. use "@home" to find icons with the tag "home" and "=home" to find icons with the name "home"

* `amount` - _required_ - the maximum number of icons which you'd like to receive (will be multiplied by platforms count, if you didn't specify the platform and didn't set the 'exact_amount' parameter)
* `offset` - _required_ - the offset from the first received result
* `platform` - _required_ - the style of the icons
    Possible values: all, ios7, ios11, win8, win10, android, androidL, color, office, ultraviolet, nolan, p1em, dotty, dusk, Dusk_Wired, cotton, doodle, flat_round.
* `language` - _required_ - the language code to get localized result
    Possible values: en-US, fr-FR, de-DE, it-IT, pt-BR, pl-PL, ru-RU, es-ES, zh-CN, ja-JP.
* `exact_amount` - _required_

### From a Collection

### From Separate Icons

## License

**flow**ground :- Telekom iPaaS / icons-8-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
