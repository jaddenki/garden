## [file.gallery](https://file.gallery/)

germinate a site from files, directories, and .DS_Store.

### setup

- `npm i`
- read [https://github.com/inchkev/garden/blob/main/README.md](https://github.com/inchkev/garden/blob/main/README.md)

### changelog

- 4/26/25:
  - performance enhancements, parallelize async operations
  - sort order is now name localeAware, might affect some display orders. previously, it was in the order readdir() returned
- 2/16/25: tweaked `formal.ejs` to be a bit less formal
- 4/12/24: add text-size-adjust (and webkit equiv)
- 4/8/24: for markdown files,
  - display file size
  - add `md` class to divs, add margins to inner tags
- 10/17/23: added gray border around items
- 10/9/23: added max recursion depth argument, defaults to 3
- 10/6/23: you can `node cultivate.js DIR` now!
  - just be very careful what directory you specify...

### license

- `src/` — `parse.py` by [Thomas Zhu](https://github.com/hanwenzhu) is licensed under the MIT license. all other source code (in `src/`) is licensed under the [Apache License 2.0](http://www.apache.org/licenses/LICENSE-2.0).
  - if modified, indicate it by adding it to the header comment, e.g. "modified by \[name\]: add jpeg xl support"
- `views/` — all templates and their styles are licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).
  - if modified, indicate it in the attribution, e.g. "modified by \[name\]"

for published websites, CC attribution only in the html source is sufficient. i'd appreciate a link to https://kevin.garden/ or https://file.gallery/ in the attribution. a visible reference on the website itself would be nice too. thank you!
