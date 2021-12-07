# copytool

## Summary
Static website.

## What it does
Forms a list of languages that have ISO 639-1 codes assigned to them.

Copies sentence(s) in the given language to the clipboard when an item of the list is clicked.

Options:
- Output Format
    - Plain text (default)
    - String encoded as a URI component
- Output Mode
    - All sentences (default)
    - One random sentence
- Sentence Separator
    - New line (default)
    - Space (`&nbsp;`)
    - None (for space-less languages)
- Times Repeat (default: 1, max.: 100)

Page layout:  
Tabs controls  
Filters controls  
Preview area  
Language list

List layout:
<table>
    <tr>
        <td>ISO 639-1 code</td>
        <td>Number of sentences in the "database"</td>
        <td>ISO language name in English and Russian</td>
    </tr>
</table>

"Database" is a Map object.

## Resources
Sentences were parsed from [Tatoeba](https://tatoeba.org/en/) beforehand.

ISO 639-1 codes were parsed from [Wikipedia](https://en.wikipedia.org/wiki/Main_Page) beforehand.

## How to install
Not required (portable).

## Changelog

### version 2 (2021.12.07)
- Added version number to the `title` tag
- Added copied language indicator below the `textarea` tag
- Added favs list
- Removed icons in tabs labels
- Removed auto scroll to top on copying to clipboard
- Tweaked color scheme
