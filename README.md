# Swapy Site i18n
This project contains the files with Swapy' website texts in different languages. You are free to contribute to this project, helping us to translate our website or even improve the existing translations.

For doubts: contact at swapy dot network

## How to contribute?

#### If you are familiar with Github
To contribute, you should fork this repository to your own account, create or improve the translations, and make a pull request containing the language and country the contribution stands for.

#### If you are not familiar with Github
To contribute, you should download the [en-US template](https://s3.us-east-2.amazonaws.com/swapynetwork/en-US.zip) and the [guide](https://s3.us-east-2.amazonaws.com/swapynetwork/guide.zip) containing the website screen capture indicating the text locations. Then, unzip the en-US.zip file, open the folder, and edit each .json file, one by one using you favorite text editor. The format is key:value in which you should only translate the value entry, keeping the key intact.

### Editing the .json files
We suggest you to use a text editor such as [Sublime Text](https://www.sublimetext.com/) to edit the .json files. Any other text editors may work too, including the very basic notepad or unix-like vi, vim, and nano.

### Understanding the pattern
Each language directory is organized as bellow:

    \layouts
    .... layout.json ---------- contains texts related to the website layout
    .... layoutbounty.json ---- contains texts related to the bounty website layout
    \partials
    .... footer.json ---------- contains texts related to home (and other pages) footer
    .... footerdownload.json -- contains texts related to download/try-alpha footer
    .... talk-to-us.json ------ contains texts related to talk to us section
    bounty.json --------------- contains texts related to bounty home page
    contact.json -------------- contains texts related to contact page
    download.json ------------- contains texts related to download/try-alpha page
    faq.json ------------------ contains texts related to team page
    home.json ----------------- contains texts related to home/index page
    rules.json ---------------- contains texts related to team page
    team.json ----------------- contains texts related to team page

You should create or modify the folder that represents the locale/language you are working for. For example, if you would like to create the translations for Japanese, you should use ja-JP as the language folder name. Please, use [this link](https://msdn.microsoft.com/en-us/library/ee825488(v=cs.20).aspx) as a reference to language codes.

To visualize the texts keys in the website, you can use the ['guide'](https://github.com/SwapyNetwork/swapy-site-i18n/tree/master/guide) folder as a reference. It follows the same pattern as the language folders and contains a picture for each of these parts for the  ([layout](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/layouts/layout.png), [layout bounty](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/layouts/layoutbounty.png), [footer](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/partials/footer.png), [footer download](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/partials/footerdownload.png), [talk-to-us](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/partials/talk-to-us.png), [bounty home](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/bounty.png), [contact](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/contact.png), [download](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/download.png), [faq](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/faq.png), [home](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/home.png), [bounty rules](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/rules.png), and [team](https://github.com/swapynetwork/swapy-site-i18n/blob/master/guide/team.png)).

The text files follow the JSON pattern, so the structure is organized as a key/value pair. Only the value part should be translated. Keep the keys exactly the same.

### We appreciate your help to spread the word in as many languages as we can! Thanks!
