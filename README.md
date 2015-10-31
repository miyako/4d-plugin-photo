# 4d-plugin-photo
Get picture from Apple's Photo.app by its ID.

```
  //1: with original 
  //0: apparently photo.app wants to export jpg be default 

$photo:=Photos get picture ("pJRMAmn%R4S9qClanASXmg";Photos with original)

SET PICTURE TO PASTEBOARD($photo)
```
