<p align="center">
<img src="images/api.png" width="256" height="256"/>
<br/>
<h3 align="center">Password Generator Rest Api</h3>
<p align="center">Source code for Password-Generator-Rest-API.</p>
<h2></h2>
</p>
<br />

<p align="center">
<a href="../../issues"><img src="https://img.shields.io/github/issues/aminbeigi/Password-Generator-Rest-API.svg?style=flat-square" /></a>
<a href="../../pulls"><img src="https://img.shields.io/github/issues-pr/aminbeigi/Password-Generator-Rest-API.svg?style=flat-square" /></a>
<img src="https://img.shields.io/github/license/aminbeigi/Password-Generator-Rest-API?style=flat-square">
</p>

## Description
Password_Generator-Rest-API takes words as input or randomly generates them from a wordlist and then finds related/similar words. Then the related words are concatenated and made to be more cryptic looking. All this data is put inside a dict and is given to get requests as a response.

## Example
`.../password/random/3`
```json
[
  {
    words: [
      "promise",
      "letter"
    ],
    related words: [
      "marry",
      "informing"
    ],
    password: "mARryInfOrm1ng"
  },
  {
    words: [
      "past",
      "good"
    ],
    related words: [
      "participle",
      "shepherd"
    ],
    password: "pArt1cipLE$hePherD"
  }
]
```
`.../password/cat&computer/2`
```json
[
  {
    words: [
      "cat",
      "computer"
    ],
    related words: [
      "kitten",
      "programmer"
    ],
    password: "K|tteNprogramMeR"
  },
  {
    words: [
      "cat",
      "computer"
    ],
    related words: [
      "feline",
      "macintosh"
    ],
    password: "F3|INemAC|ntosH"
  }
]
```

## Requirements
* Python 3.9.1+

## Acknowledgements
API: https://www.datamuse.com/api/

## Contributions
Contributions are always welcome!  
Just make a [pull request](../../pulls).

## Licence
MIT license
