***Git release Notes***

// installer git-release-notes

$ ./bin/install

//générer les releases notes

$ cd mon-projet

$ git-release-notes <tag_v1>..<tag_v2> ../ADTools/git-release-notes/ad_markdown.ejs > changelog.markdown

***Abandonned strings***

//Restez dans ce dossier et renseignez le path de votre projet iOS (le dossier)

$ ./AbandonedStrings /Users/your-username/path/to/source/code

***Generate wording file from an iOS .strings or an Android XML file***

// Utilisez la commande ./bin/generate_wording_ios pour iOS, résultat dans wording_iOS
// Utilisez la commande ./bin/generate_wording_android pour Android, résultat dans wording_android