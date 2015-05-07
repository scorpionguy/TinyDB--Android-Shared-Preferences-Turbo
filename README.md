# TinyDB -- Android-Shared-Preferences-Turbo

This class simplifies calls to SharedPreferences in a line of code. It can also do more like: saving a list of strings, integers and saving images. All in 1 line of code!

Example usage:
```
TinyDB tinydb = new TinyDB(context);

//int
tinydb.put("clickCount", 2);
//float
tinydb.put("xPoint", 3.6f);
//long
tinydb.put("userCount", 39832L);
// string
tinydb.put("userName", "john");
// bolean
tinydb.put("isUserMale", true); 

tinydb.putList("MyUsers", mUsersArray);
tinydb.putImagePNG("DropBox/WorkImages", "MeAtlunch.png", lunchBitmap);

//These plus the corresponding get methods are all included
```


This is just an example of how easy it is to use. There are many more usefull methods included in the class. Enjoy :)
