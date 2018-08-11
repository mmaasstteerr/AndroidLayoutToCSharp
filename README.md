# AndroidLayoutToCSharp

Tiny prgram that converts android xml's into c# properties. It can save a few minutes of your life ^^
It runs on UWP.

![](https://github.com/Drutol/AndroidLayoutToCSharp/blob/master/github/screenshot.png)

## Features

- [x] Convert Android XML layout to C# properties.
- [x] Recursive resolution of layouts in `<include>` elements.
- [x] Creating ViewHolders

## Additional stuff

* You can add `tools:managedTypeName` attribute to use custom Type for properties. Useful when you have override Type name in library binding project.
* Warns about duplicated IDs, helpful when layout in `<include>` contains the same ID.
