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
1. (Optional) Add and nest plugin instances for extra feature.
1. See plugin render content that matches configuration and nested plugin instances.

[dcms-link]: https://github.com/django-cms/djangocms-link

## Features

1. Render a list/dictionary of data as `<table>` or `<dl>`.
1. Uses supported, nested plugin instances to incorporate extra features.
      <details>

      | feature | supported by |
      | :- | :- |
      | item key as hyperlink | [`taccsite_data_list`][dcms-link] |

      </details>

## Caveats

- The provided styles are only a sample and are not suitable for all designs.

  _Your app should override the template or stylesheet to load its own styles._
