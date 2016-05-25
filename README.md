# Strossle JavaScript Style Guide
The his JavaScript style guide is based on the [eslint-config-airbnb-base](https://github.com/airbnb/javascript) style guide.

## Table of Contents
1. [Arrow Functions](#arrow-functions)
1. [Curly Braces](#curly-braces)
1. [Indentation](#indentation)

## Arrow functions
<a name="arrow-functions--parenthesis"></a><a name="1.1"></a>
* [1.1](#arrow-functions--parenthesis) **Parenthesis**: Arrow function arguments should always be surrounded by parenthesis.
```javascript
array.map(element => element.id); // bad

array.map((element) => { return element.id; }); // good
```
<a name="arrow-functions--braces"></a><a name="1.2"></a>
* [1.2](#arrow-functions--braces) **Braces**: Arrow function bodies should always be surrounded by braces.
```javascript
array.map((element) => element.id); // bad

array.map((element) => { return element.id; });
```

## Curly Braces
<a name="curly-braces--braces"></a><a name="2.1"></a>
* [2.1](#curly-braces--braces) **Braces**: Both signle and multi-statment blocks should be surrounded by braces.
```javascript
if (i < 10) i++; // bad

if (i < 10) { // good
    i++;
}

```

## Indentation
<a name="indentation--indentation"></a><a name="4.1"></a>
* [3.1](#indentation--indentation) **Width**: Indentation levels should be 4 spaces. We feel that 4 spaces makes
it easier to distinguish between indentation levels.
