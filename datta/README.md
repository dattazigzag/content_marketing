# Content Marketing

Repository to hold markdown files for articles.

## Guidelines

```txt
your_short_name/
└── Art_01_short_title/
    ├── README.md                # Main article file
    └── assets/
        ├── _cover.png           # Cover image (1500x750 for Medium, 1500x600 for GitHub)
        ├── diagram.png          # Other image assets
        ├── screenshot.png
        └── demo.gif             # Must be 320px wide
```

1. Directory Organization
   1. Base Path Format: `[your_short_name]/Art_[article no.]_[short_title]`.
   2. Example: `john_doe/Art_01_react_hooks`.
2. Asset Management
   1. Location: All assets must be in `assets/` subdirectory.
   2. Full Path: `[your_short_name]/Art_[article no.]_[short_title]/assets/`.
   3. Example: `john_doe/Art_01_react_hooks/assets/`.
3. Essential Files
   1. Main Article: Name it `README.md` (ensures automatic rendering on GitHub)
   2. Cover Image: Must be named `_cover.png` and stored in `[your_short_name]/Art_[article no.]_[short_title]/assets/_cover.png`.
      1. Medium size: 1500x750 pixels
      2. GitHub size: 1500x600 pixels
      3. Cover img embedding:

         ```html
         <img src="assets/_cover.png" width="100%" alt="Description">
         ```

4. Asset embeddings:
   1. GIF Requirements:
      1. Must be resized to 320px width
      2. Use HTML tags for embedding gifs and other images:

         ```html
         <img src="assets/animation.gif" width="320" alt="Description">
         ```

         ### Note for Editors

         If your markdown linter flags HTML tags, you can:

         1. Review the issue: [markdownlint md033](https://github.com/DavidAnson/markdownlint/blob/v0.36.1/doc/md033.md)
         2. Configure exceptions: [VS Code markdownlint configuration](https://github.com/DavidAnson/vscode-markdownlint#configure)

