# Jekyll Test Cases

This repository is for Jekyll sites used to attempt to reproduce issues
with Jekyll. They are named by the related repository and issue number.

## Usage

```bash
~$ git clone git://github.com/jekyll/cases.git
~/cases$ cd cases
~/cases/jekyll-123$ # pick your case and cd into that
~/cases/jekyll-123$ jekyll build --trace
```

Always run with the latest version of Jekyll unless a `Gemfile` is
included.
