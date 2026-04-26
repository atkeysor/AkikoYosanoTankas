# Akiko Yosano's 399 Tankas

Selected English Translations of <em>Midaregami</em>

By Allia Keysor, Boston College

## About

This project is a digital edition of Jane Reichhold's and Machiko Kobayashi's (R/K's) <em>A Girl with Tangled Hair: The 399 tanka in Midaregami</em> (2013), the first full, print version of Akiko Yosano's 399 Tanka Poems. These tankas are paired with their Romaji transliterations (recorded in R/K's print edition) and the original Japanese Kana. The aim of this project is to compare the stylistic and syntactical decisions that are made when translating Japanese poetry to English; therefore, the TEI file also contains ten selected English tankas from Sam Hamill's and Keiko Matsui Gibson's 1996 translation of Yosano's work, as well as Dennis Maloney's and Hide Oshiro's 2012 collection (citations below).

<em>A Girl with Tangled Hair: The 399 Tanka in</em> Midaregami - Tangled Hair. Translated by Jane Reichhold and Machiko Kobayashi, AHA Books, 2013.

<em>River of Stars: Selected Poems of Yosano Akiko,</em> Translated by Sam Hamill and Keiko Matsui Gibson, 1996.

<em>Tangled Hair: Selected Tanka of Yosano Akiko,</em> Translated by Dennis Maloney and Hide Oshiro, 2012.
 

## Files you need to edit

1. `/_config.yml` Put the title and general info for your project, and define what pages should appear in the nav bar
2. `/_pages/` Add Markdown (.md) files for each page you defined in the _config.yml file (check out the [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet/))
3. `/assets/img/` Put any images you want in your site here
4. `/README.md` (this file), to put your information and project description
5. `CITATION.cff` Edit this file to put in your information for automatical bibliographic citation generation on Github

## Extra files to edit

1. `/_sass/theme-settings.scss` Edit this file to quickly change colors and fonts for the site. (Use [this site](https://htmlcolorcodes.com/color-picker/) to generate the hex color codes)
2. `/_sass/custom-styles.scss` Edit this file to put any custom CSS you want to style your site. ([Learn basic css here](https://www.w3schools.com/w3css/defaulT.asp))

## Local Development

* Follow [this guide](https://jekyllrb.com/docs/installation/) to install Ruby and Jekyll
* Install [Node](https://nodejs.org/en)
* `git clone` this repo and then `cd` inside the directory
* Comment out the `url` and `baseurl` lines of `_config.yml` when working locally
* Install Ruby dependencies by running `bundle install`
* Install Node dependencies by running `npm install`
* Run the server with `bundle exec jekyll serve`

## Acknowledgements

Jekyll & Tailwind Setup based on [TailPages](https://github.com/harrywang/tailpages) by [Harry Wang](https://harrywang.me/) (Chinese: 王建楠)
