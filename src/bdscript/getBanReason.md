# $getBanReason[]
Gets the user's ban reason.


## Syntax
```
$getBanReason[User ID;(Guild ID)]
```

### Parameters
- `User ID` `(Type: Snowflake || Flag: Required)`: User to get the ban reason for
- `Guild ID` `(Type: Snowflake || Flag: Optional)`: The server id from which to get the ban reason.


## Example
```
$nomention
Ban Reason: $getBanReason[154148273307910144]
```

![example](https://user-images.githubusercontent.com/113303649/209688041-a4a229d1-9b7b-40bc-b85f-9acb5c8e0011.png)
