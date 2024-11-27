# Content Marketing

Repository to hold markdown files for articles.

## Rules

- Directory naming rule

```bash
# Directory path example
[your_short_name]/Art_[article no.]_[short_title]
```

- Name the article file `README.md` in its directory to enable automatic rendering when viewing that directory on GitHub.
- All the assets must be stored in a assets sub directory.
  
```bash
# Directory path example
[your_short_name]/Art_[article no.]_[short_title]/assets/
```

- An article must have a cover image. Cover is size: and is called `_cover.png`
- Amongst all the assets, if using gifs, they must be resized to 320 px. In markdown it is usually done using html tags.

```bash
# Directory path example
<img src="[PATH to article dir]/assets/[file_name].gif" width="320" alt="[some short descriptive text]">
```

> Your editor’s linter may complain. More about it [here](https://github.com/DavidAnson/markdownlint/blob/v0.36.1/doc/md033.md) and how to fix it [here](https://github.com/DavidAnson/vscode-markdownlint#configure).
