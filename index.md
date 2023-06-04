# My H1 Header
### My H3 Header
![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)
```python
hrs = input("Enter Hours:")
h = float(hrs)
rate = input("Enter Rate Per Hour:")
r = float(rate)
if h > 40:
    base = h * r
    ot = (h - 40.0) * (r * 0.5)
    total = base + ot
    print(total)
else:
    total = h * r
    print(total)
 ```
- [x] Use List syntax
- [x] This item is complete
- [ ] This item is not complete
