---
title: "HTML"
_old_id: "86"
_old_uri: "2.x/administering-your-site/dashboards/dashboard-widget-types/dashboard-widget-type-html"
---

The HTML Dashboard Widget Type displays straight HTML - nothing else - in a widget. Useful for simple messages and other data.

## Usage

Simply place your HTML in the content panel, and it will load the HTML in the widget.

This widget type also supports cached placeholders and element calls (uncached calls will not work). So, for example, you can use:

``` php
Hello, [[+modx.user.username]]!
```

To output the username of the logged-in user. You can also call Snippets, like so:

``` php
[[MyDashboardSnippet]]
```

Note that in snippets there is no "active resource", so snippets referencing `$modx->resource` will have issues.

## See Also

1. [Dashboard Widget Type - File](building-sites/client-proofing/dashboards/widget-types/file)
2. [Dashboard Widget Type - HTML](building-sites/client-proofing/dashboards/widget-types/html)
3. [Dashboard Widget Type - Inline PHP](building-sites/client-proofing/dashboards/widget-types/inline-php)
4. [Dashboard Widget Type - Snippet](building-sites/client-proofing/dashboards/widget-types/snippet)
