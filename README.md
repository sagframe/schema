# sqltoy schema

XSD schemas for [sqltoy-orm](https://github.com/sagframe/sagacity-sqltoy), served via GitHub Pages.

| Schema | URL (use this in `xsi:schemaLocation`) |
| --- | --- |
| sql xml | https://sagframe.github.io/schema/sqltoy.xsd |
| cache-translate xml | https://sagframe.github.io/schema/sqltoy-translate.xsd |
| quickvo.xml | https://sagframe.github.io/schema/quickvo.xsd |

Example:

```xml
<sqltoy xmlns="http://www.sagframe.com/schema/sqltoy"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:schemaLocation="http://www.sagframe.com/schema/sqltoy https://sagframe.github.io/schema/sqltoy.xsd">
```

> The namespace (`http://www.sagframe.com/schema/...`) is the schema identity and never changes;
> only the location hint points here. These files are kept in sync with sqltoy-orm releases.
