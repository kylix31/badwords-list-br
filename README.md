# badwords-list-br

A forked from badwords-list with some aditional brazilians words.

Inspired by [badwords](https://github.com/MauriceButler/badwords)

This data has been exposed as an object that contains

- an array
- an object
- a regular expression

depending on what is required for your purposes.

# Install

    npm install badwords-list

# Usage

```
var list = require('badwords-list'),
	array = list.array,
	object = list.object,
	regex = list.regex;
```

# Testing

#### Requires

- Mocha
- better-assert

```
npm test
```

**or**

```
REPORTER=spec make
```

**or**

```
mocha
```
