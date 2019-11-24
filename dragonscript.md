![DragonScript](https://i.imgur.com/3NJoebP.png)

![LICENSE](https://img.shields.io/badge/license-BSD--3--Clause-blue)
![VERSION](https://img.shields.io/badge/version-0.1.0-green)

DragonScript is a lightly modified version of Microsoft's [TypeScript](http://www.typescriptlang.org) that
was created to make it even more like C++.

### Table Of Contents
- [Setup](#setup)
- [Documentation](#documentation)
- [Support](#support)

### Setup
At this time while the Project is in alpha, the setup and features of DragonScript are invite only.

### Documentation
In this section you will see a master file that allows you to see how DragonScript works by using
all of it's unique features in a single code block
```drs
;; This is a comment in DragonScript

;; Import node modules (Specifics are a WIP)
#include <fs>
#include <./custom.exports.file>

;; Storing variables

;; A "const" variable
cvar langName: String* = 'DragonScript';
;; A "let" variable
tvar created: Int* = 2019;

;; Type demonstrations
tvar myString: String* = 'Demo';
tvar myFloat: Float* = 3.14;
tvar myInt: Int* = 69;
tvar myArray: Array* = ['a','b','c'];
tvar myObject: Object* = :> name: 'DragonScript', year: 2019 <:;
tvar myJson: Json* = myArray || myObject;

;; Read a JSON file function
operation readJsonFile(path: Path*): Json* :>
  cvar fileContent: String* = fs::readFileSync(path, :> encoding: 'utf8' <:);
  return JSON::parse(fileContent);
<:
```
