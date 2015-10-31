# 4d-plugin-photo
Get picture from Apple's Photo.app by its ID.

Example
---
```
  //1: with original 
  //0: apparently photo.app wants to export jpg be default 

$photo:=Photos get picture ("pJRMAmn%R4S9qClanASXmg";Photos with original)

SET PICTURE TO PASTEBOARD($photo)
```

###Note

Internally using [Cocoa Scripting Bridge](https://developer.apple.com/library/mac/documentation/Cocoa/Conceptual/ScriptingBridgeConcepts/Introduction/Introduction.html).
