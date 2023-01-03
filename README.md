# APA-like with DOI for MS Word bibliography
APA-like bibliography template (APALike-Frank.XSL) for extending native APA in "References -- Bibliography" in MS Word 2016/ 2019/ 365

## Features
- Base style : APA v6
- Simple and clear in-line citations : 
 - - `<max author names>` : Long authors namelist supressed (max to display = 2)
 - - `<comma>` : Comma "," supressed
 - - `<in-line title>` : long title supressed
 - - `<repeated authors>` : Repeated authors' initials supressed
- DOI (and URL) emphasized for academic resources :
 - - `<important input field>` :  For articles, conference papers, book, book chapter, report, etc.
 - - `<auto URL>` : Generates a clickable link based on DOI or URL, e.g., "doi:10.1016/j.landurbplan.2022.104505" -> doi:[10.1016/j.landurbplan.2022.104505](https://doi.org/10.1016/j.landurbplan.2022.104505")
- ArXiv preprints :
 - - `<input field>` :  Type "arXiv:1801.01234" in the "Pages"
 - - `<auto URL>` : Generates clickable link to the ArXiv Preprint, e.g., "arXiv:1801.01234" -> <https://arxiv.org/abs/1801.01234>

## Install
- `Windows` : Copy the .xsl file to "%appdata%/Microsoft/Bibliography/Style"
- `Mac` : Copy the .xsl file to "/Applications/Microsoft\ Word.app/Contents/Resources/Style"

## Basic use
- MS Word Menu - References - Citations & Bibliography - choose Style: "APALike-DOI"
- User Manual from Microsoft support: <https://support.microsoft.com/en-us/office/create-a-bibliography-citations-and-references-17686589-4824-4940-9c69-342c289fa2a5>

## License
- MIT License
