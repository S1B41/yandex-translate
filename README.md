# yandex-translate

Translate text in Android using Yandex Translate API

## What is that?

Android Java class translates text using Yandex Cloud Translation API

## How it works?

It takes three parameters, the text which will be translated, the source language and the target language.
It performs the translation in background and returns a string with the result

## Features

* Translating text using Yandex Cloud Translation API
* Only one short class thus Easy to use and understand

## How to use it?

* Clone the repository or download the class from src and put it somewhere in your project folder
* Import the package
* Create an object of the class
```java
YandexTranslate yandexTranslate = new YandexTranslate();
```
* Perform the translation by invoking the execute method, but first save the result in a String:
```java
String result = yandexTranslate.execute("the text to be translated", "en", "de").get();
```
* The second parameter is the source language, the third is the terget language
* Do whatever you want with the result!

## License

The Class is licensed under the [GNU General Public License v3.0](https://www.gnu.org/licenses/gpl-3.0.en.html)
