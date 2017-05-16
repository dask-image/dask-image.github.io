# Purpose

This is the source for the dask-image webpage. It makes use of [Jekyll][1] and [@jasonlong][2]'s [Cayman theme][4] to build it. Page generation is also done by [GitHub Pages][3].

You can see the generated webpage at [https://dask-image.github.io/][5] or build and host it locally.

# Usage

Using the terminal, simply clone this repo

```
$ git clone https://github.com/dask-image/dask-image.github.io.git
```

Change to the directory.

```
$ cd dask-image.github.io
```

Install the required gems.

```
$ bundle install
```

Have Jekyll generate the webpage (`-w` for live updating).

```
$ jekyll serve [-w]
```

Open [`http://localhost:4000`]( http://localhost:4000 ) in your browser.


# Contributing

Bug reports and pull requests are welcome at [https://github.com/dask-image/dask-image.github.io][6] on GitHub.

[1]: http://jekyllrb.com/
[2]: https://github.com/jasonlong
[3]: http://pages.github.com/
[4]: https://github.com/jasonlong/cayman-theme
[5]: https://dask-image.github.io
[6]: https://github.com/dask-image/dask-image.github.io
