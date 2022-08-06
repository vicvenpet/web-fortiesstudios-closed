## 40's Studios

[![license](https://img.shields.io/github/license/fortiesstudios/web-fortiesstudios)](https://github.com/fortiesstudios/web-fortiesstudios/blob/main/LICENSE)

40's Studios website. Simple and elegant.

## Download

/*

## How to use

Clone the repository with GitBash or similar.

## API

/*

### Activity

``` kotlin
setFullScreen()
showToolbar() // Support and native
hideToolbar() // Support and native
```

### Context

``` kotlin
getClipboardManager()
copyTextToClipboard(value: String)
copyUriToClipboard(uri: Uri)
getTextFromClipboard(): CharSequence
getUriFromClipboard(): Uri?
getPreferences(): SharedPreferences
getPreferences(name: String, mode: Int): SharedPreferences
```

### SharedPreferences

#### SharedPreferences.use(lambda)
It automatically applies after lambda execution
``` kotlin
val sharedPrefs = context.getPreferences()
sharedPrefs.edit {
    putBoolean("first_use", false) // This refers to sharedPrefs instance
}
```

### Versions

These methods are static.

``` kotlin 
