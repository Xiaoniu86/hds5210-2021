Part 1:  5/5

Part 2:  5/5

One comment on how you wrote some of the for average lenght of stay.  If you repeat a function call like this, then it will actually do the calculation twice.  It's better practice to run the function once and assign a variable to the output.

```
        if los(v['admit'],v['discharge'],v['diagnosis']) != 0:
            sum_los=sum_los+los(v['admit'],v['discharge'],v['diagnosis'])
```