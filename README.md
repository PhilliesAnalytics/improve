# improve this code
```
# The below function checks whether a string is a palindrome.
# Please explain, in 250 words or less, how you'd improve the code and why.
def is_palindrone(s):
    r=""
    for c in s:
        r = c +r
    for x in range(0, len(s)):
        if s[x] == r[x]:
            x = True
        else:
            return False
    return x
```
