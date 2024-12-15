# ADB Commands for TextNow App Developed by [ATik HaSan](https://atikhasan.com)

<p align="center">
  <img src="https://raw.githubusercontent.com/atikhasan392/textnow/refs/heads/main/logo/saucelabs-logo.png" alt="Sauce Labs Logo" width="150">
  <img src="https://raw.githubusercontent.com/atikhasan392/textnow/refs/heads/main/logo/textnow-logo.png" alt="TextNow Logo" width="150">
  
</p>

## Download the TextNow App
Run the following command using `adb shell` to download the TextNow app:

```bash
adb shell am start -a android.intent.action.VIEW -d "https://play.google.com/store/apps/details?id=com.enflick.android.TextNow"
```

If you're using Sauce Labs, simply run this command:

```bash
adb shell am start -a android.intent.action.VIEW -d "https://play.google.com/store/apps/details?id=com.enflick.android.TextNow"
```

## Clear Cache for TextNow App
To clear the cache of the TextNow app, run the following command using `adb shell`:

```bash
adb shell pm clear com.enflick.android.TextNow
```

If you're using Sauce Labs, simply run this command:

```bash
adb shell pm clear com.enflick.android.TextNow
