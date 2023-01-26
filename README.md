hugo-bootstrap-fix
==================

A fork of [appernetic/hugo-bootstrap-premium](https://github.com/appernetic/hugo-bootstrap-premium) for some compatibility fixes.

## Installation with Hugo

```
$ cd your_site_repo/
$ mkdir themes
$ cd themes
$ git clone https://github.com/mikan/hugo-bootstrap-fix
```

See the [official Hugo themes documentation](http://gohugo.io/themes/installing) for more info.

## Usage

This theme expects a relatively standard Hugo blog/personal site layout:
```
.
└── content
    ├── post
    |   ├── post1.md
    |   └── post2.sv.md // format for language specific files.
    ├── code
    |   ├── project1.md
    |   ├── project2.md
    ├── exempel.sv.md  // format for language specific files.
    └── other_page.md

```

Just run `hugo --theme=hugo-bootstrap-fix` to generate your site!

## Configuration

### Hugo

An example of what your site's `hugo.toml` could look like.
All theme-specific parameters are under `[params]` and standard Hugo parameters are used where possible.

``` toml
theme = "hugo-bootstrap-fix"
```

## License

Open sourced under the [MIT license](LICENSE).
