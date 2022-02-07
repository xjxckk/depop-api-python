### Depop API in Python

```
# Sample code to get all the followers of a Depop account

import depop

followers = depop.get_followers('paydayvintage') # https://www.depop.com/paydayvintage/
for follower in followers:
    print(follower['username'])
```
