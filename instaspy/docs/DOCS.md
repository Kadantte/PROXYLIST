## Import & Initialize
```python
from instaspy import Instagram

cookie = 'your cookie string'
ig = Instagram(cookie=cookie)
```
## Get basic account info
```python
print(ig.name) # Instagram Name 
print(ig.username) # Instagram Username 
print(ig.id) # Instagram ID

# or use 

print(ig.user_data(username=ig.username)) # output: dict
```

## Get user info
```python
username = 'ivanfmh15'
print(ig.user_data(username=username)) # output: dict
```
