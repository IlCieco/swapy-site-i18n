# Swapy Site i18n
This project contains the files with texts to Swapy in couple different languages. You are free to contribute to this project, helping us to translate our website or even improve the existing translations.

## How to contribute?
To contribute, you should fork this repository to your own account, create or improve the translations, and make a pull request containing the language and country the contribution stands for.

### Understanding the pattern
Each language directory is organized as bellow:

    \layouts
    .... layout.json -------- contains texts related to the website layout
    \partials
    .... talk-to-us.json ---- contains texts related to talk to us section
    contact.json ------------ contains texts related to contact page
    home.json --------------- contains texts related to home/index page
    team.json --------------- contains texts related to team page
    faq.json --------------- contains texts related to team page

You should create or modify the folder that represents the locale/language you are working for. For example, if you would like to create the translations for Japanese, you should use ja-JP as the language folder name. Please, use [this link](https://msdn.microsoft.com/en-us/library/ee825488(v=cs.20).aspx) as a reference to language codes.

To visualize the texts keys in the website, you can use the ['guide'](https://github.com/SwapyNetwork/swapy-site-i18n/tree/master/guide) folder as a reference. It follows the same pattern as the language folders and contains a picture for each of these parts ([layout](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/layouts/layout.png), [talk-to-us](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/partials/talk-to-us.png), [contact](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/contact.png), [home](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/home.png) and [team](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/team.png)).

The text files follow the JSON pattern, so the structure is organized as a key/value pair. Only the value part should be translated. Keep the keys exactly the same.

### We appreciate your help to spread the word in as many languages as we can! Thanks!
