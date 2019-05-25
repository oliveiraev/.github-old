# [@oliveiraev](https://github.com/oliveiraev)'s default community files

This repo provide vanilla community files and language-agnostic git files to
serve as starting point for other repositories.

## What are community files?

Community files are "metacontent" that provide help to users on how to use the
project, where to find help, how to contribute and how to report issues.

Repository services such as [Github](https://github.com) and
[Gitlab](https://gitlab.com) also make use of specific files as templates like
[issue](https://help.github.com/en/articles/creating-issue-templates-for-your-repository)
and pull request templates.

## Why are they important?

Cuz they give **you** autonomy to get start by yourself without needing of
another human to guide you. Since every project has potential to become
worldwide at anytime, the core maintainers couldn't be available to help you
due to business-times or different timezones. Also, if a small project become
famous, the sole single maintainer wouldn't be able to answer all the people
questions, including the repeated ones.

Here comes files like [README](README.md), that explains the project purposes
and give you directions about how to go further.
[CONTRIBUTING](CONTRIBUTING.md), containing coding-standards, pull-request
policies, how to run the tests and all the other development cool stuff.
[LICENSE](LICENSE.md), that explains what you can and - even more important -
**can't** do with the code and the software that it produces.

## Where are they from?

Github team started a project called [OpenSource Guide](https://opensource.guide)
with tips about [how to build welcoming communities](https://opensource.guide/building-community/),
[leadership and governance](https://opensource.guide/leadership-and-governance/),
[code of conduct](https://opensource.guide/code-of-conduct/) and [legal stuff](https://opensource.guide/legal/)
for maintainers among other things and [how to contribute](https://opensource.guide/how-to-contribute/)
for people looking for existent projects that need some help.

## What about *"git files"*?

Mainly: .gitignore and .gitattributes

.gitignore provides a list of files that shouldn't be versioned through the
repository. Sample of these files are build artifacts and temporary-intermediary
files like cache or tempfiles and IDE/editors settings.

.gitattributes tells git how to behave with versioned files, like how to parse
them, show its diffs, if it should apply any filter/algorithm and also helps
handling linebreaks between different operational systems.

<!-- vim: set ai si sta et sw=4 sts=4 fenc=utf-8 nobomb eol ff=unix ft=markdown: -->
