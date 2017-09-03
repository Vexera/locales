# Translation Guide
If you are going to help translate vexera into multiple languages, please read below.

## How to translate
We handle translations on [i18n.vexera.io](https://i18n.vexera.io/projects/vexera/bot/), where they should all be made. **Do not submit merge requests to this repostiory, they will be denied!**

For translating strings, there is 2 cases:
 1. The string hasn't been translated. In this case, you can directly submit a translation, unless there is multiple active contributors for this language (see #2).
 
 2. The string has already been translated and you want to update/fix the translation. In this case, **do not update the translation, but make a suggestion.** This suggestion, if upvoted by active contributors will then automatically replace the current translation.
 
In either case, you should also follow the rules below.

## Read the comments
...especially for the first two strings (if you start a new language).
They can contains some useful informations to translate the string correctly.
 
## Variables
Text contained inside `{{}}` is a variable, these **must** not be replaced, these are replaced with the correct information when that response is generated. These can be moved around anywhere within that response so it makes sense with whatever language you are translating into.

## Formatting
In the responses, you will see lots of these so that they look nice on discord. These **must** be maintained during translation. Heres what they look like. https://support.discordapp.com/hc/en-us/articles/210298617-Markdown-Text-101-Chat-Formatting-Bold-Italic-Underline-


## Parts that must not be translated.
Some parts of strings must not be translated, e.g parts that directly reference commands e.g 'Choose from **add, remove**'.
There is one exception: **none** and **cancel** can be translated.  
If you are unsure about what should be translated and not translated, feel free to leave a comment on the translation or ask at our guild.

## I have translated a string, where it will be visible in Vexera?
**Short answer**: On the next update (from few hours to few days).

**Long answer**: Translations are frequently pushed to this repository. You should see your changes in it in the few next hours. Then, the translations of this repository are pulled to the Vexera source code (mostly when we do updates). The translations are finally visible when we deploy a new version (these deployments are made infrenquently, from one per day to one per week).
