# Parlametrics Data

Parlametrics is a database codings features of conversational style. 

This repository is for pulling, formatting, validating and cleaning the Parlametrics dataset.

Data is presented in three data tables within raw/

| file             | description                                              |
|------------------|----------------------------------------------------------|
| data.csv         | Codings of the phrasing and breath patterns in each song |
| conversation.csv | Metadata on each conversation                            |
| societies.csv    | Metadata on the societies from which the songs originate |

## Getting started

To see the list of available commands and scripts type into your terminal:

`make help`

<small><strong>Note:</strong> This code has been tested for Mac/Windows, but if you are on a windows, please submit a pull request so we can make it easier to run. This step assumes you have a working distribution of `make`. For installation instructions please update XCode or follow the specific guidelines for installing `make` on your system. </small>

## Collect google drive data

`make download`

