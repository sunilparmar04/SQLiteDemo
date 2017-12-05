# SQLiteDemo
This is the simplest example of SQLite for All CURD operations.

## FriendDB
This is the Main database Handler class.


### Add data in SQLite Table
 On click of button set value of friend.
```
 Friend friendinfo = new Friend();
            friendinfo.name = name;
            friendinfo.email = email;
            friendinfo.mobile = number;
            friendinfo.id = friend_id;

// call this method to add data
long rowInserted = FriendDB.getInstance(MainActivity.this).addFriend(friendinfo);

if(rowInserted!=-1){
//data inserted into SQLite
}else{
//getting error
}

```

Enter friend details

<img  src="https://github.com/sunilparmar04/SQLiteDemo/blob/master/ScreenShots/output.png " width="40%">

