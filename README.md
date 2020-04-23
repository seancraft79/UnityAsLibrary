# UnityAsLibrary
Unity as a library sample project

1. Change app package name to whatever you want.

2. Change Unity library path in settings.gradle
```
    include ':app'
    include ':unityLibrary'
    project(':unityLibrary').projectDir=new File('..\\Android_Exported\\unityLibrary')
```

3. Add OverridingUnityActivity to unityLibrary with new package.

4. That's it. Unity will overwrite binary of unityLibrary on ever new export.