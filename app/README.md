# ActionBar Helper Class and Example

## Summary

This CommonJS class for Appcelerator Titanium wraps the Android ActionBar functionalities so it is super easy to implement.

## Example

To use the ActionBarHelper class, simply require it and create an instance, passing your window as argument.

Note: To work with the ActionBar your Android activity needs to exist.  This means that initial settings for the ActionBar need to be performed on the "Open" event of your Window.

```
var ABH=require('actionbarhelper').actionBarHelper;
var actionBarHelper=new ABH($.index);	

actionBarHelper.setTitle('This is my window title');
```

## License

MIT - [http://alco.mit-license.org/]()