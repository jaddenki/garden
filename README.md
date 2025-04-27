## file.gallery

to setup, please read [https://github.com/inchkev/garden/blob/main/README.md](https://github.com/inchkev/garden/blob/main/README.md)

but also `npm i`

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
