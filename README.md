# Instagram-UnfollowBot
Basic Python code allowing you to unfollow them annoying people and just get rid of all those accounts you don't pay attention to this tool has many other features 

Functionality: 

- **Info**: Show report

- **Follow users**: from tag, from location, from a list or follow back who you do not follow back

- **Unfollow users**: who do not follow you back or all of them

---------------------

## Usage: 

**Show report (who follows, unfollows, follows you back):**
```
python main.py -u USERNAME -p PASSWORD -o info
```

**Follow users using the tag you introduce:**

```
python main.py -u USERNAME -p PASSWORD -o follow-tag -t TAG
```

**Follow users from a location:**

```
python main.py -u USERNAME -p PASSWORD -o follow-location -t LOCATION_ID
```

**Follow back all the users who you don't follow back:**
```
python main.py -u USERNAME -p PASSWORD -o super-followback
```

**Follow users from a list:**

```
python main.py -u USERNAME -p PASSWORD -o follow-list -t USER_LIST
```

**Unfollow all the users who don't follow you back:**
```
python main.py -u USERNAME -p PASSWORD -o super-unfollow
```
**NOTE**: Fill "whitelist.txt" file with the accounts you will never want to unfollow


**Unfollow all the users:**
```
python main.py -u USERNAME -p PASSWORD -o unfollow-all
```
**NOTE**: Fill "whitelist.txt" file with the accounts you will never want to unfollow
