# Translation Guide
If you are going to help translate vexera into multiple languages, please read below.

## How to translate
We handle translations on [i18n.vexera.io](https://i18n.vexera.io/projects/vexera/bot/), where they should all be made. **Do not submit merge requests to this repostiory, they will be denied!**


For translating strings, there are 2 cases:
 1. If you are part of our [translation program](https://goo.gl/forms/Wal2fKup3HjmTblA3), you can directly submit translations from the [website](https://i18n.vexera.io/projects/vexera/bot/).

 2. If you are not part of this program, do not hesitate to [apply](https://goo.gl/forms/Wal2fKup3HjmTblA3)! Until your application is approved,
you can only suggest strings. To have these strings validated, you must ask an approved translator or a staff member.

In either case, you should also follow the rules below.

## Read the comments
They can contains some useful informations to translate the string correctly.
 
## Variables
Text contained inside `{{…}}` is a variable, these **must** not be replaced, these are replaced with the correct information when that response is generated. These can be moved around anywhere within that response so it makes sense with whatever language you are translating into.

## Formatting
In the responses, you will see lots of these so that they look nice on discord. These **must** be maintained during translation. [Heres what they look like.](https://support.discordapp.com/hc/en-us/articles/210298617)

## Parts that must not be translated.
Some parts of strings must not be translated, e.g parts that directly reference commands e.g 'Choose from **add, remove**'.  
If you are unsure about what should be translated and not translated, feel free to leave a comment on the translation or ask at [our guild](https://vexera.io/support).

## I have translated a string, where will it be visible in Vexera?
**Short answer**: On the next update (from few hours to few days) if enough strings are translated.

**Long answer**: Translations are frequently pushed to this repository. You should see your changes in it in the few next hours. Then, the translations of this repository are pulled to the Vexera source code (mostly when we do updates). The translations are finally visible when we deploy a new version (these deployments are made infrenquently, from one per day to one per week).  
Also, please note that translations should be added to [a list](/index.js) to be shown by Vexera. This allows us to only show languages with enough translated strings (some languages have less than 10 translated strings…). If your language is not in [this list](/index.js), you can bug us at [our guild](https://vexera.io/support).
