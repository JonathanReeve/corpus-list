# Corpus List 
A structured list of textual corpora, created for use with corpus downloader. This list is read by the Python module and command-line program [corpus-downloader](https://github.com/DH-Box/corpus-downloader), originally developed for use in [DHBox](http://dhbox.org). 

## How to Add Your Corpus

Do you own or maintain a textual corpus? Please fork this repository and add it to the list. Here are a list of current fields and their descriptions: 

`shortname`: a short and easy-to-type name for your corpus, e.g. `shc` for the corpus “Shakespeare His Contemporaries.” 
`title`: the full name for your corpus, e.g. “Shakespeare His Contemporaries.” 
`categories`: a disciplinary label you can assign to your corpus. If if it’s mostly of interest to classics scholars, write “classics.” Current values include “literature,” “classics,” and “history,” but feel free to add your own. 
`languages`: The ISO 649-2 language code for the language(s) of your corpus. Examples include `deu` (German), `eng` (English), `enm` (Middle English), and `fra` (French). For a more complete list, [check here](https://www.loc.gov/standards/iso639-2/php/code_list.php). 
`text`: information about the actual text(s) of your corpus. 
  `markup`: how the text is encoded. E.g. `TXT` (plain text), `HTML` (HTML files), or `TEI` (TEI XML). 
  `url`: the URL for your textual corpus, e.g. `http://www.folgerdigitaltexts.org/download/txt/FolgerDigitalTexts_TXT_Complete.zip`
  `file-format`: the file format of the URL above. In the above example, `zip`. 

```
- shortname: perseus-c-greek
  title: Perseus Canonical Greek
  categories: classics
  authors: multiple
  languages: grc
  text: 
    markup: TEI
    url: https://github.com/PerseusDL/canonical-greekLit.git
    file-format: git
```
