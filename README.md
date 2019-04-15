# Ionic ZLIB - Unity Package Manager edition

Ionic's zlib library is an often used C# library. This is simply a wrapper of the package in Unity's Package Manager format.

No copyright over the zlib code itself is implied or taken. All I've done is wrapped the existing code so that you can link it from Unity's Package Manager

# Add to your project
Open the manifest.json for your project and add the following entry to your list of dependencies

```"com.ionic.zlib": "https://github.com/PixelWizards/com.ionic.zlib.git",```

For example:
```
  "dependencies": {
    "com.newtonsoft.json": "https://github.com/PixelWizards/com.ionic.zlib.git",
    "com.unity.ads": "2.0.8",
    "com.unity.analytics": "3.2.2",
    "com.unity.collab-proxy": "1.2.15",
    ...
    }
 }```
