The [Dododex Taming Calculator for Ark: Survival Evolved](http://www.dododex.com) is being translated into every language and your help is needed! Translations are crowdsourced — edits made to this Github project will be included in a future version of the app. Continued edits and new languages will be added through Github.

**Translators get Dododex Pro for free!** After contributing at least half of your language's translations, contact me (dan14lev[at]gmail.com) to get a promo code for the ad-free version of Dododex.

[Join the Translator Chat!](https://discord.gg/KvmRSSV)

![Translate Dododex](https://raw.githubusercontent.com/dododex/translations/master/translate.png?2)

## 1. TRANSLATING DODODEX

1. **Open [translations.js](translations.js) and click "Edit"**
1. **If your language is not there, add it.**

   1. To add a new language, copy and paste the entire English section ("en").
   1. Change the "en" to your language's code ([list of language codes](https://sites.google.com/site/tomihasa/google-language-codes))). (Regional languages (`es-mx` vs. `es`) are only recommended if the translations will have a noticable difference. When possible, try to translate for the general language to simplify the project.)
   1. Translate each of the phrases.
1. **Translate the phrases into your language.** 

   Look at the English version of a phrase, and then add a translation to the corresponding section for your language (language codes are listed below). It's best to translate from English to your language, as other languages may not yet be verified.

   If you are unsure of any translation, please keep it blank so someone else can add it later. Do not add notes to your translation, or add multiple translations. Instead, open an Issue (detailed below) to discuss the correct translation. 

1. **Add your name to the list of translators.** If you'd like, feel free to add your name and (optionally) a URL the bottom of the file.
1. **Submit your changes** This will be submitted as a [pull request](https://help.github.com/articles/using-pull-requests/) and will be approved. 

*(If you have any trouble with these instructions, but still want to help, please contact me at dan14lev at gmail.com or [Join the Translator Chat](https://discord.gg/KvmRSSV)!)*

## 2. TRANSLATING CREATURE NAMES & CATEGORIES
1. **Open [creatures.json](creatures.json) or [categories.json](categories.json) and click "Edit."**
1. **Add translated names in your language.**
   
   If a creature (or entire language) is not officially translated in-game, DO NOT translate it, Dododex will fallback to the English version. The goal is to make the creature names accessible, but expected -- don't translate JUST to translate. If "Ovis" is not translated in-game, do not translate it to "Sheep" in your language, as users would likely look for "Ovis" on Dododex. If a creature does not have a translation, simply omit it rather than creating a copy of the English translation. However, for not-Latin characters please consider transliterating if you think it would be more helpful to speakers of your language. 
   
   **IMPORTANT**: Regional versions of languages (For example: Brazilian Portuguese / "PT-BR") are also supported. However, it is beneficial to also have the base language ("PT"), since all PT-XX languages will fall back on the base one. If there are any discrepencies between regional languages, please open an issue on Github so it can be logged.
   
   All creature names and categories should be in Title Case (_Example_: "Attack Drone" not "attack drone").

   Please keep languages in alphabetical order, according to their language code.
1. Add your name to [translations.js](translations.js) if you'd like to be credited!

## NOTES

* **Phrasing & Punctuation:** If the English phrase includes characters like exclaimation points, parenthases, colons, ellipses, be sure these are included if they are applicable in your language. If you are unsure, try to understand the context of the phrase and try your best to match it in your language.
* **Abbreviations & Long Words:** Some English terms are intentionally abbreviated because of a lack of interface space ("pts.", "mins."). If possible, please try to abbreviate these in your language into something short that people would understand. In addition, there are some terms in English that are already short and also need to fit in a small space. For example, "Use" and "Max" are headings on the main taming table that need to fit in a small column. If possible, try to keep these words short. Abbreviate if necessary. A different, shorter word may be used if it its meaning is still applicable. 
* **Special Characters:** Special (non-Latin) characters such as ä or 渡 can be inserted into the file directly without translating them to HTML entities (don't use `&auml;` or `&#x6E21;`). If you add a double quote, please escape it with a backslash: `\"`.
* **Submit Your Progress:** If you don't have much time to volunteer and prefer to translate these phrases over many days, it's best to submit your progress ocassionally in case someone else submits translations for that same language.
* **Starting A Discussion:** If you're unsure of any translations, have questions about a phrase or its context, or think that a translation is incorrect, start a discussion by [creating an issue](https://github.com/dododex/translations/issues/new). Please include the language in the title of the issue.
* **Variables:** Some phrases have variables in them where a term will be inserted into the sentence. These are indicated with a `{0}`. For example, `There are {0} creatures` could become `There are 50 creatures` and the number would increment as more creatures are added. All translations must include this variable. If phrasing in your language can vary depending on what the variable actually is (for example, grammatical gender), please do your best to accomidate what the variable could be. If appropriate, rephrase so the line works better in your language.

## TRANSLATION PROGRESS

| Code | Language | % of Users* | [Interface](translations.js) | [Creatures](creatures.json) | [Categories](categories.json) |
| ---- | -------- | ----------- | --------- | --------- | ---------- |
| de | German               | 37.4% | ✅ | ✅ | ✅
| fr | French               | 19.4% | ✅ | ✅ | Partial
| pt | Portuguese           |  8.4% | ✅ |
| es | Spanish              |  6.1% | ✅ | ✅ | ✅
| ru | Russian              |  7.6% | ✅ | ✅ | ✅
| nl | Dutch                |  4.0% | ✅ |
| it | Italian              |  3.8% | ✅ | ✅ | ✅
| pl | Polish               |  2.4% | ✅ |
| zh | Chinese (Simplified) |  ~2.2% | ✅ | ✅
| zh-hant | Chinese (Taditional) |  ?% | ✅ | ✅
| da | Danish               |  1.3% | ✅ | Partial
| tr | Turkish              |  1.2% | ✅ |
| sv | Swedish              |  1.0% |   |
| cs | Czech                |  0.7% | ✅ |
| nb | Norwegian            |  0.6% | ✅ |
| hu | Hungarian            |  0.5% |   |
| th | Thai                 |  0.5% | ✅ | 
| ar | Arabic               |  0.4% | ✅ | | ✅
| ko | Korean               |  0.3% | ✅ |
| fi | Finnish              |  0.3% | ✅ |
| ja | Japanese             |  0.3% | ✅ | ✅
| he | Hebrew               |  0.2% | ✅ |
| hr | Croatian             |  0.2% | ✅ |
| sk | Slovak               |  0.1% |   |
| ro | Romanian             |  0.1% | ✅ |
| el | Greek                |  0.1% | ✅ |
| id | Indonesian           | <0.1% | ✅ |


_*Percent of non-English Dododex users_
