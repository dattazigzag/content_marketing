# Content Marketing

Repository to hold markdown files for articles.

## Rules

1. Directory naming rule

```bash
# Directory path example
[your_short_name]/Art_[article no.]_[short_title]
```

2. Name the article file `README.md` in its directory to enable automatic rendering when viewing that directory on GitHub.
3. All the assets must be stored in a assets sub directory.
  
```bash
# Directory path example
[your_short_name]/Art_[article no.]_[short_title]/assets/
```

4. An article must have a cover image and it's size must be: 1500x750 (for medium) or 1500x600 (for github).
5. The cover image must be called: `_cover.png`, so that it is always on the top of the directory.
6. Amongst all the assets, if you are using gifs, they must be resized to 320 px. In markdown it is usually done using html tags.

```bash
# Directory path example
<img src="[PATH to article dir]/assets/[file_name].gif" width="320" alt="[some short descriptive text]">
```

> Your editor’s linter may complain. More about it [here](https://github.com/DavidAnson/markdownlint/blob/v0.36.1/doc/md033.md) and how to fix it [here](https://github.com/DavidAnson/vscode-markdownlint#configure).
