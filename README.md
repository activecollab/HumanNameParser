# Human Name Parser

[![Build Status](https://travis-ci.org/activecollab/humannameparser.svg?branch=master)](https://travis-ci.org/activecollab/humannameparser)

Takes human names of arbitrary complexity and various formats and parses initial, first name, last name, middle name, nicknames etc. Example:

```php
use ActiveCollab\HumanNameParser\Parser;

$name = new Parser("Peter O'Toole");

print $name->getFirst() . "\n";
print $name->getLast();
```

## Running tests

`cd` to this directory and run:

```bash
phpunit
```
