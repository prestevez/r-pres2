# prestevez/r-pres2

Dockerfile for personal R docker image. Based on [rocker-org/r-ver](https://github.com/rocker-org/rocker-versioned2).

Status of CI build: [![CircleCI](https://circleci.com/gh/prestevez/r-pres/tree/master.svg?style=svg)](https://circleci.com/gh/prestevez/r-pres/tree/master)

## Base image

[x] rocker/r-ver:4

## Binaries

[x] Pandoc
[x] Quarto
[x] Radian

## R packages

Should only contain bare minimum of packages.

[x] tidyverse
[x] tidymodels
[ ] ggthemes
[x] RMarkdown
[x] devtools
[ ] Cairo
[ ] car
[ ] texreg
[ ] downloader
[ ] data.table
[x] parallel # Already installed with base
[x] DBI


## Rpackages required for vscode
[ ] languageserver
[ ] httpgd
[ ] vscDebugger


## To do

[x] Create non-root user
[ ] Create image for both architectures
    [ ] `linux/amd64` (Intel chips)
    [ ] `linux/arm64` (ARM/Mac chips)
