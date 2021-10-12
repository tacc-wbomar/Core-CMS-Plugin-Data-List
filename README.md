## Texas Advanced Computing Center
# Django CMS Plugin: "Data List"

This plugin renders a data dictionary as `<table>` or `<dl>`.

- __`__plugin_name__`__: `taccsite_data_list`
- __`__PluginName__`__: `TaccsiteDataList`
- __"Plugin Name"__: "Data List"

## Quick Start

1. Follow https://github.com/tacc-wbomar/Core-CMS-Plugin/wiki/Core-CMS-Plugin-Usage-Quick-Start.

## Usage

1. Add instance of "Data List" plugin to a page.
1. Configure the plugin instance.
1. Add and nest instance(s) of "Data List Item" plugin (key/value pair).
    - (Optional) Add and nest instance of supported plugin for extra feature.
        <details>

        | feature | supported by |
        | :- | :- |
        | item key as hyperlink | [`taccsite_data_list`][dcms-link] |

        </details>
1. See plugin render content that matches configuration and nested plugin instances.

[dcms-link]: https://github.com/django-cms/djangocms-link

## Features

1. Render a list/dictionary of data as `<table>` or `<dl>`.
1. Render a key (of an key/value pair a.k.a. item) as text or a hyperlink.

## Caveats

- The provided styles are only a sample and are not suitable for all designs.

  _Your app should override the template or stylesheet to load its own styles._
