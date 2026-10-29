# RPM Specfile support for GitHub Linguist

Syntax highlighting for the GitHub web renderer through [GitHub Linguist](https://github.com/github-linguist/linguist).

## Example Grammar

![Screenshot](https://raw.githubusercontent.com/terrapkg/language-rpm-spec/master/linguist-rpm-spec-example.png)

## Background

RPM Package Manager files are the packaging format of many popular Linux
distributions such as RedHat and CentOS, openSuSE and the Fedora Project. RPMs
use a specfile to describe how to take upstream sources and deploy them onto a
Linux operating system.

A specfile ends in .spec and is usually named for the project's source code that
is to be deployed. The process of making an RPM from the various parts, known
as building, is driven by instructions in the specfile.

High quality specfiles are a key part of providing repeatable and consistent
experiences delivering programs, fonts, graphics, utilities, and even entire
operating system environments to the end user or system administrator. Syntax
highlighting is a method of helping improve the quality of edited files
through catching simple but well-hidden typos, syntax errors and misplaced
keywords.

## Contributing

Contributions are welcome! Please fork and make any pull requests needed for
corrections, new snippets, grammar tweaks, or anything else.

### Note

This is a fork of https://github.com/waveclaw/language-rpm-spec, which provided Atom and GitHub Linguist support, but is no longer maintained and missing many new RPM features.
