# 4d-plugin-photo
Get picture from Apple's Photos.app by its ID.

### Platform

| carbon | cocoa | win32 | win64 |
|:------:|:-----:|:---------:|:---------:|
|<img src="https://cloud.githubusercontent.com/assets/1725068/22371562/1b091f0a-e4db-11e6-8458-8653954a7cce.png" width="24" height="24" />|<img src="https://cloud.githubusercontent.com/assets/1725068/22371562/1b091f0a-e4db-11e6-8458-8653954a7cce.png" width="24" height="24" />|||

### Alternative solution

[4d-plugin-apple-file-promises](https://github.com/miyako/4d-plugin-apple-file-promises)

## Examples

```
  //1: with original 
  //0: apparently photo.app wants to export jpg be default 

$photo:=Photos get picture ("pJRMAmn%R4S9qClanASXmg";Photos with original)

SET PICTURE TO PASTEBOARD($photo)
```

Internally using [Cocoa Scripting Bridge](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/ScriptingBridgeConcepts/Introduction/Introduction.html).

c.f. [forums.4d.fr](http://forums.4d.fr/Post//17035664/1/)
