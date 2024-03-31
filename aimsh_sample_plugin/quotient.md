---
type: python
description: Calculate quotient of two numbers
expects:
  dividend: number to be divided (numerator)
  divisor: number to divide by (denominator)
response:
  quotient: Quotient of two numbers
  greeting: Greeting constructed by invoking another function
---
All text outside the first set of code fences (```) is ignored.

```python
q1 = float(dividend)/float(divisor)
quotient = str(q1)
greeting = self.hello(name="Rick", action="smell")
```
