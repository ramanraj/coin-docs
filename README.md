# coin-docs

Constitutional instruments and documents

## Synopsis

This is an attempt to keep track of amendments to constitutional instruments and documents relevant to India in particular. The Indian Constitution has 100+ amendments and using git one can view the original constitution along with the amendments made to it. Square brackets are added to the original text with the amendment number as a superscript. The deletions are marked with strikethrough font effect along with new text introduced by the amendment.

## Motivation

Print versions omit the original text deleted by an amendment which is sometimes necessary to understand the amendment. This project aims to provide views of the constitution after each amendment, and any deleted text is shown with strikethrough font effect. 

## Installation

Git is required to be installed to be able to browse through the versions of the constitution.

Installing git on gnu/linux, mac, windows and from source is explained at:

https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

To download and install the documents in this project, clone from:

https://github.com/ramanraj/coin-docs.git

One can also download a zip file of the project files by using this url:

https://github.com/ramanraj/coin-docs/archive/master.zip

After installing git and downloading the coin-docs files, use git commands to checkout into desired branch corresponding to the amendment to browse the coi.pdf file version.

## How to use

### On gnu/linux systems:

```
cd /usr/local/src/coin-docs

git tag -a

```

gives the following output

```
coi-000
  coi-001
  coi-002
  coi-003
  coi-004
  coi-005
  coi-006
  coi-007
  coi-008
* master
  remotes/origin/HEAD -> origin/master
  remotes/origin/coi-000
  remotes/origin/coi-001
  remotes/origin/coi-002
  remotes/origin/coi-003
  remotes/origin/coi-004
  remotes/origin/coi-005
  remotes/origin/coi-006
  remotes/origin/coi-007
  remotes/origin/coi-008
  remotes/origin/master
```

To view the original constitution as enacted on 29-11-1949, enter:
```
git checkout coi-000
```
point browser or pdf reader to /usr/local/src/coin-docs/coi.pdf

To view the constitution as it stood after the 1st amendment, enter:
```
git checkout coi-001
```
point browser or pdf reader to /usr/local/src/coin-docs/coi.pdf

coi.pdf versions upto the 8th amendment are available here.

## License

This work is dedicated to the public domain.
