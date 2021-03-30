Score: 48/50

In `heart()`, you've got an issue that's preventing your code from running (-2):

```
    if risks==0:
        score_risk=0
    elif risks=1 or risks=2:   <---- These should be double-equal signs
        score_risk=1
    else:
        score_risk=2
```


In your `framingham()` code, you could have simplified the code a bit by writing the long equation only once, but use different variables for the different coefficient values.

Nice work on the rest of it.