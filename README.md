## Numberlang

A small language for representing calculations.
Targeted at implementing map projections via code injection.

Goals

* Non-crazy syntax, somewhat familiar to Javascript programmers
* No side effects allowed
* Type annotations
* Compact syntax
* Secure: no access to Javascript objects
* Only numbers allowed: no other types
* Tiny implementation

Possible features:

* TODO constants

```javascript
var HALFPI = 1.5707963267948966;
var FORTPI = 0.78539816339744833;
var PI = 3.14159265358979323846;
var TWOPI = 6.2831853071795864769;
var A = 6378137;
var D2R = Math.PI / 180;
```

* Base Math library

atan
log
fabs
cos
sin
