# RNI18N

## About i18n
The term "i18n" is derived from the first letter "i," the last letter "n," and the number "18" in between, representing the 18 letters between "i" and "n" in the word "internationalization."

The main goal of i18n is to make software accessible and user-friendly for users worldwide, regardless of their native language or location. By implementing i18n practices, developers can create applications that can be easily translated and localized to cater to the linguistic and cultural preferences of diverse user bases.

Key aspects of i18n include:

String Externalization: All user-visible strings and text are extracted from the source code and placed in external resource files. These resource files, known as "translation files" or "language packs," contain the translations of the strings for different languages.

Locale and Language Support: The application should support various locales and languages. Each locale represents a specific region or country, while the language defines the linguistic elements used in the user interface.

Date and Time Formatting: Date and time formats should be adapted based on the user's locale, taking into account factors such as date order, time zone, and localized month and day names.

Number Formatting: Numbers, currencies, and numeric formats should be displayed according to the user's locale, including decimal separators, thousand separators, and currency symbols.

Text Direction: Some languages are written from right to left (RTL), while others are written from left to right (LTR). Proper text direction handling is essential for supporting RTL languages.

Localization Testing: Rigorous testing should be performed to ensure the accuracy and correctness of the translations and the application's behavior under various locales.

By following i18n best practices, developers can create applications that are more inclusive and accessible to a global audience, fostering better user experiences and increasing the application's reach in international markets.

## About this project. 

Repository bootstraped with [React-Native-Template-Nave-Typescript](https://github.com/naveteam/react-native-nave-typescript) to handle I18n on react-native applications. In the Home screen you will find a simple screen with a button to go to a Settings screen and select the desired language to your application, after changed, this language is stored and you can go back to Home screen, or even close and re-open the app to see the language updated. 

## :wrench: Running

Clone the repository

```sh
  git clone https://github.com/lucasGabrielDeAA/RNI18N.git
```

If you use SSH keys on Github

```sh
  git clone git@github.com:lucasGabrielDeAA/RNI18N.git
```

```sh
  cd RNI18N
```

Installing the dependencies

```sh
  yarn && yarn pod-install
```

Running the application

Android

```sh
  yarn android
```

IOS

```sh
  yarn ios
```

This app uses the following dependencies to manage internationalization

- [React-i18next](https://github.com/i18next/react-i18next)
- [Intl](https://github.com/andyearnshaw/Intl.js)

The locales files, and the `i18n` configuration file from this project can be found [here](https://github.com/lucasGabrielDeAA/RNI18N/tree/main/src/locales)

- Built with :heart:&nbsp; by [Lucas Gabriel](https://github.com/lucasGabrielDeAA)
