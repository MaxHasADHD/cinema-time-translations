# Cinema Time Translations
This project contains the localization files for my app [Cinema Time](https://cinematime.app)

## How to contribute
At the moment this repo contains the `.strings` files from Xcode containing the translations. To add new translations find one of the supported language files such as `de.lproj` and open the `localizable.strings` file. From there edit the right side of the string that hasn't been translated yet. The format of a translation is as follows:

```
/* Comment describing the use case / english text */
"Key - Do not change this" = "Translation - Update this"
```

After adding the translations, submit a pull request and I'll review it for the next version of the app.

In the future I hope to upload an `xliff` file instead which can be opened from many different online programs and from there it will be much easier to add translations.
