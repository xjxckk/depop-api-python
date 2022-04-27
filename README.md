# Depop API in Python
### Features:
* Login with your Depop account
* Get an accounts followers
* Get an accounts following
* Follow people
* Unfollow people
* Get people who have bought your items
* Get people who have reviewed your items
* Post items
* Edit your items
* Refresh/bump your items
* Send messages
* Reply to messages
* Search for items

### Sample code to get all the followers of a Depop account
```
import depop

followers = depop.get_followers('paydayvintage') # https://www.depop.com/paydayvintage/
for follower in followers:
    print(follower['username'])
```

The output of get_followers is in [followers.json](https://github.com/xjxckk/depop-api-python/blob/main/followers.json)

### How to get access:
Contact me on Telegram: @xJxckk

Message me on Discord: jx#2099
