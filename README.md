# Docdown v1.0.0

A simple JSDoc to Markdown documentation generator.

## Documentation

The documentation for Docdown can be viewed here: [/doc/README.md](https://github.com/jdalton/docdown/blob/master/doc/README.md#readme)

For a list of upcoming features, check out our [roadmap](https://github.com/jdalton/docdown/wiki/Roadmap).

## Installation and usage

Usage example:

```php
require("docdown.php");

// generate Markdown
$markdown = docdown(array(
  "path" => $filepath,
  "url"  => "https://github.com/username/project/blob/master/my.js"
));
```
