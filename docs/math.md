# Some notes on math typesetting


## Line breaks
Because of the way hugo renders markdown, addition signs will create a list
where your math should be—all in all that's a bad place to be in. Basically,
it can be summarized as

**wrong**
```
c^2 = a^2
+ b^2
```

**right**
```
c^2 = a^2 +
b^2
```

I don't particularly love this—it's pretty far from how TeX behaves—but it's
either this or doing all the html by hand, which gets pretty difficult after
a while.


## Primes
Again, because hugo is rendering markdown, it will interpret `a'` operators
as `a’`. The (in)elegant solution to this is to write `a^\prime`—that solution
definitely works, but it looks awful.
