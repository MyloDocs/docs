# Getting Started

There are a few things needed to create your first Documentation Site. You need a GitHub repo that contains your markdown files. And you need to sign up for mylodocs.com



## Versioning 

Mylodocs will only include GitHub branches that start with `v`. So for version `1.2` there would be a branch called `v1.2`.



## Github Repo Structure

In order to have the best looking documentation site your github needs to contain a few files. Without those your site will not function correctly.

#### Menu

To set up your menu you need to have a file called `DIGEST.md` in the root of your repo. It should be structured like below. I would suggest your first item be the Overview like below. See the next section about the `_index.md` file. 

```markdown
* [Overview](_index.md)

## Prologue

* [Introduction and Installaton](prologue/introduction-and-installaton.md)
* [Contributing Guide](prologue/contributing-guide.md)
* [How To Contribute](prologue/how-to-contribute.md)
* [Release Cycle](prologue/release-cycle.md)

## External Links

* [Github](https://github.com)
```

Anything in `DIGEST.md` will be displayed in the menu. Make sure you're links are correct. 

#### Version Overview

One more file you must have in the root of your repo is `_index.md`. This is the markdown file that will get rendered as a summary for your version. It's the file that gets render at `https://subdomain.mylodocs.com/docsitename/v1/` This should contain overview information. 

There are a few things you need to remember. Mylodocs will ignore anything that starts with a `.` such as `.gitignore`.
