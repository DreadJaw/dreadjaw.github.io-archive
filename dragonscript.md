![DragonScript](https://i.imgur.com/3NJoebP.png)

![LICENSE](https://img.shields.io/badge/license-BSD--3--Clause-blue)
![VERSION](https://img.shields.io/badge/version-0.1.0-green)

DragonScript is a lightly modified version of Microsoft's [TypeScript](http://www.typescriptlang.org) that
was created to make it even more like C++.

### Table Of Contents
- [Setup](#setup)
- [Definitions](#definitions)
- [Basic Examples](#examples)
- [Support](#support)

### Setup
At this time while the Project is in alpha, the setup and features of DragonScript are invite only.

### Definitions
DragonScript, much like TypeScript, uses it's own interfaces and definitions. You will find an
example of some of these below.
- `String*` - `<string>` - Any string is compatible
- `Float*` - `<number>` - A float number
- `Int*` - `<number>` - An integer number
- `Array*` - `<any[]>` - Any array is applicable
- `Object*` - `<{[key: string]: any;}>` - A Javascript object
- `Json*` - `<{[key: string]: any;} | any[]>` - The potential content of a JSON
- `Any*` - `<any>` - Anything
