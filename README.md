# Workshop "Quarto: A library to run them all?"

Materials for the MQ quarto 2023 workshop: _"Quarto: a Library to run them all?"_, by Lorenzo Campoli.


## Overview

Using literate programming is a widespread practice amongst data scientists.
Chances are that you may have come across, or even used, one of the two more
mature projects, Rmarkdown or jupyter notebooks, to present results, do
exploratory analysis, author academic articles or complete books or even
perform complete analyses. While both solutions can be used with multiple
programming languages, the decision of whether to use one or the other is
almost certain to be exclusively based on that: the vast majority of R users
will opt for Rmarkdown while python users will favour jupyter notebooks.  At
least until now, with Quarto being mature enough to become a game-changer.
Quarto is a language-agnostic software that it's based on pandoc to render
files combining markdown and code into multiple ranges of formats and outputs.
This means it can be used with either R, Phython, Julia or Observable without
any other dependencies.  This collaborative workshop will be organised around 3
stages: 

1. a brief theoretical introduction and instructions; 
2. a task that participants may chose from the different use cases provided
   (i.e. generating a single document, migrating from Rmarkdown or jupyter,
   creating a book or generating interactive content); and 
3. discussion and conclusions.

Participants in this workshop will have enough depth of breath and practice to
evaluate how feasible is to use Quarto in different scenarios and, ultimately,
if it can become the one-tool for reproducible scientific publishing,
regardless of your language of choice. 


## Pre-requisites

In order to take part in this workshop you will need to have the following software in your laptop:

1. Quarto installed (see [instructions here](https://quarto.org/docs/get-started/))
2. Git
3. Editor of your choice, preferably RStudio and/or Visual Studio Code (or its FLOSS version, VSCodium)


All the software used in this workshop is available for GNU/Linux, Windows and MacOS.

## Installation instructions

1. Clone repo: `git clone git@github.com:lkampoli/quarto-workshop.git`
2. Install quarto's binaries: https://quarto.org/docs/get-started/
3. Recreate virtual environment (not implemented yet)

## File structure

To be done later.

```
slides/       <-- Slides for the workshop.
cases/        <-- Quarto use cases, each case in a folder.
|-- <case_n>  <-- Each case should reside in a folder.
|-- template  <-- Template for documenting the process.

```

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center"><a href="https://github.com/lkampoli"><img src="https://avatars.githubusercontent.com/u/40017451?v=4" width="100px;" alt=""/><br /><sub><b>Lorenzo Campoli</b></sub></a><br /><a href="https://github.com/lkampoli/quarto-workshop/commits?author=lkampoli" title="Code">💻</a> <a href="#ideas-lkmapoli" title="Ideas, Planning, & Feedback">🤔</a> <a href="#talk-lkmapoli" title="Talks">📢</a> <a href="https://github.com/lkampoli/quarto-workshop/commits?author=lkampoli" title="Documentation">📖</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

It is a collaborative project, this means that: A) Contributions of any kind are welcome!; and B) following the [all-contributors specification](https://allcontributors.org/) and being grateful is a requirement.

If you believe you must be credited, please do it in [this issue](https://github.com/WarwickCIM/quarto-workshop/issues/1).

## Attendees

Please, introduce yourselves in [this issue](https://github.com/WarwickCIM/quarto-workshop/issues/17)
