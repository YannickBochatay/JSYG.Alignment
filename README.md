# JSYG.Alignment
Alignment plugin for JSYG framework

### Demo
[http://yannickbochatay.github.io/JSYG.Alignment/](http://yannickbochatay.github.io/JSYG.Alignment/)

### Installation

##### with npm
```shell
npm install jsyg-alignment
```

##### with bower
```shell
bower install jsyg-alignment
```

### Examples with webpack/babel

##### with the constructor
```javascript
import Alignment from "jsyg-alignment"

let alignElmts = new Alignment("#svgContainer > *")

alignElmts.alignTop().alignLeft()
```
##### as a JSYG plugin
```javascript
import JSYG from "jsyg"
import "jsyg-alignment"

JSYG("#svgContainer > *").align("top").align("left")
```