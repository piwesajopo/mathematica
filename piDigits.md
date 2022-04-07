# Obtaining Pi Digits using Mathematica Formulas

**You can test these at [Wolframalpha.com](https://www.wolframalpha.com/)**

### Get N decimal digits from Pi

**Get First 120 digits:**
```
N[Pi, 120]
```

**On Hex Format:**
```
BaseForm[N[ Pi, 120], 16]
```

**On Octal Format:**
```
BaseForm[N[ Pi, 120], 8]
```

**Note:** The above expressions will conver the 120 decimal digits value (i.e. they will not show 120 hex or octal digits)


### Get X Base N Digits:

Get first 105 Hex digits
```
RealDigits[ Pi, 16, 105 ] [[1]]
```

Get first 145 base 3 digits:
```
RealDigits[ Pi, 3, 145 ] [[1]]
```

### Base 16 using hex numbers:
```
BaseForm[RealDigits[ Pi, 16, 105 ] [[1]], 16]
```

### As Base 16 Integer String:
```
IntegerString[RealDigits[ Pi, 16, 105 ] [[1]], 16]
```
