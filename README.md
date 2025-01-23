## Quartz

This project is based on [quartz](https://github.com/jackyzha0/quartz) using [Obsidian.md](https://obsidian.md) as the Markdown editor of choice.

## Quartz Theme
We are using [quartz-themes](https://github.com/saberzero1/quartz-themes) for theme integration.

Currently we had to modify 2 files:
  - ``justfline`` on line `2`
  - ``set-theme.js`` on line 101

I've created an issue upstream, but just for documentation this is what I changed for the theming to work.


## Dev

Update (syncrepo): ``npx quartz sync``

Build Locally: ``npx quartz build --serve``