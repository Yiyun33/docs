---
title: "XPath Contains"
url: /refguide8/xpath-contains/
---

## Overview

The `contains()` function tests whether a string attribute contains a specific string (case-insensitive) as a sub-string.

## Example

This query returns all the customers from which the name contains the string `an`:

```java {linenos=false}
//Sales.Customer[contains(Name, 'an')]
```

Customers with the name "Andy" or "Jan" will be returned, for example, because "an" is part of those names.
