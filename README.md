[![Build Status](https://travis-ci.org/concordion/concordion-timestamp-formatter-extension.svg?branch=master)](https://travis-ci.org/concordion/concordion-timestamp-formatter-extension)

This [Concordion](http://www.concordion.org) extension reformats the footer of the Concordion output to show hours, minutes and seconds rather than milliseconds.

# Introduction

A simple extension that reformats the footer of the Concordion output to show hours, minutes and seconds rather than milliseconds.

To install the extension, either annotate the fixture class with:

```java
    @Extensions(TimestampFormatterExtension.class)
```

or set the system property `concordion.extensions` to `org.concordion.ext.TimestampFormatterExtension`

This extension currently has no configuration options. Feel free to suggest enhancement ideas on our [issue list](https://github.com/concordion/concordion-timestamp-formatter-extension/issues).

# Further info

* [Specification](http://concordion.github.io/concordion-timestamp-formatter-extension/spec/TimestampFormatter.html)
* [API](http://concordion.github.io/concordion-timestamp-formatter-extension/api/index.html)