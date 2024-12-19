# ADB Commands for TextNow App. Developed by [ATik HaSan](https://atikhasan.com) ❤️

## Download the TextNow App
Run the following command using `adb shell` to download the TextNow app:

```bash
adb shell am start -a android.intent.action.VIEW -d "https://play.google.com/store/apps/details?id=com.enflick.android.TextNow"
```

If you're using Sauce Labs, simply run this command:

```bash
am start -a android.intent.action.VIEW -d "https://play.google.com/store/apps/details?id=com.enflick.android.TextNow"
```

## Clear Cache for TextNow App
To clear the cache of the TextNow app, run the following command using `adb shell`:

```bash
adb shell pm clear com.enflick.android.TextNow
```

If you're using Sauce Labs, simply run this command:

```bash
pm clear com.enflick.android.TextNow
```
## Force Stop for TextNow App
To force-stop of the TextNow app, run the following command using `adb shell`:

```bash
adb shell am force-stop com.enflick.android.TextNow
```

If you're using Sauce Labs, simply run this command:

```bash
am force-stop com.enflick.android.TextNow
```
