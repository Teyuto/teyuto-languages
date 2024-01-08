#teyuto-languages

Everyone is invited to actively participate in the translation of Teyuto, as the translations have been made available as a public project on GitHub. You can find them here: <https://github.com/Teyuto/teyuto-languages>


**Native translations available:**

*   Afrikaans

*   Albanian

*   Arabic

*   Bulgarian

*   Chinese

*   Czech

*   Danish

*   Dutch

*   English

*   Estonian

*   Finnish

*   French

*   German

*   Greek

*   Hebrew

*   Hungarian

*   Indonesian

*   Italian

*   Japanese

*   Korean

*   Latin

*   Norwegian

*   Polish

*   Portuguese (Brazilian)

*   Portuguese (European)

*   Romanian

*   Russian

*   Serbian

*   Slovenian

*   Spanish

*   Swedish

*   Turkish

*   Ukrainian

*   Vietnamese

## How it works:


Our system uses a JSON format, which associates keys and values for translations. For example, if you want to translate the text "Hello World," you need to look up the string to be translated and change the value of the corresponding key. For example, if you wish to translate it into Italian:


```javascript
English [index.json]
"HELLO_WORLD": "Hello World"
Italian [it/index.json]
"HELLO_WORLD": "Ciao Mondo"
```

## How to contribute:

**Method 1**
If you are familiar with GitHub, you can clone in project locally, edit the strings and open a Pull request.
Otherwise. you can simply open the translation page you want to edit directly from Github, search for the text to be translated, and make the changes.&#x20;
Alternatively, you can open an issue to report the desired changes.


**Method 2**
Alternatively, if you wish to use an editor, you can do so through GitLocalize. To get started, register on the official website and access Teyuto's language repository: <https://gitlocalize.com/repo/9065>

## What you can do:

There are several ways to contribute to the project, including:

*   Correct or improve existing translations.

*   Adding new translations.

*   Create new translation languages:
    To create a new translation page, please create a new **\[lang]/index.json **file with all the necessary translations, following the existing format.
