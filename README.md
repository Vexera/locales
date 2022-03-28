# Translation Guide
If you'd like to help translate Vexera into multiple languages, please read below.

## How to translate
We handle all translations on [i18n.vexera.io](https://i18n.vexera.io/projects/vexera/bot/). **Do not submit pull requests to this repository, they will be denied!**


For translating strings, there are 2 options:
 1. If you are part of our [translation program](https://i18n.vexera.io/form/), you can directly submit translations on our [website](https://i18n.vexera.io/projects/vexera/bot/)!

 2. If you are not part of our translation program, do not hesitate to [apply](https://i18n.vexera.io/form/)! If you're not an approved translator,
you can only suggest strings. To have these strings validated, you must ask an approved translator or a staff member.

In either case, you should also follow the rules below.

## Read the comments
They can contain some useful information to translate the string correctly. **Please read all comments carefully**.
 
## Variables
Text contained inside `{{…}}` is a variable. Variables **must not** be replaced as they are replaced with the correct information when that response is generated, which is out of the translators' hands. Variables can be moved around anywhere within the translation. You're free to move them around so your translation makes sense with whatever language you are translating into.

## Formatting
In the responses, you will see a lot of Markdown formatting. Markdown is used to make the messages look nicer and to highlight important information. Markdown formatting **must** be maintained during translation. [Here's how this works and what it looks like](https://support.discordapp.com/hc/en-us/articles/210298617).

## Parts that must not be translated.
Some parts of strings must not be translated, e.g. parts that directly reference commands ('Choose from **add, remove**')  
If you are unsure about what should be translated and what shouldn't, feel free to leave a comment on the translation or ask in our [support server](https://vexera.io/support), preferably in the dedicated #translators channel.

## I have translated a string, when will it be visible in Vexera?
**Short answer**: On the next update. This also depends on the amount of translations that are pending to be updated.

**Long answer**: Translations are frequently pushed to this repository. You should see your changes in it in the few next hours. Then, the translations of this repository are pulled to the Vexera source code (mostly when we do updates). The translations are finally visible when we deploy a new version (these deployments are made infrenquently).
Also, please note that translations should be added to [a list](/index.js) to be shown by Vexera. This allows us to only show languages with enough translated strings (some languages have less than 10 translated strings…). If your language is not in [this list](/index.js), you can let us know in our [support server](https://vexera.io/support).
