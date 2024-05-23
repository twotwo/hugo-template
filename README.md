# Hugo Blog Template

Template use guide. Run your web site in 5 minites.

## How to Run

### Install Hugo

```bash
$ brew install hugo # macOS
$ hugo version
hugo v0.125.7
```

See also

- [Linux](https://gohugo.io/installation/linux/)
- [Windows](https://gohugo.io/installation/windows/)
- [BSD](https://gohugo.io/installation/bsd/)
- [Development](https://gohugo.io/contribute/development/)
- [GitInfo](https://gohugo.io/methods/page/gitinfo/)

### Install Template

```bash
git clone --recurse-submodules https://github.com/twotwo/hugo-template # or
git submodule update --init --recursive
```

```bash
$ cd hugo-template
$ tree -d .
          archetypes/
          content/     # blog files
          data/
          layouts/
          public/      # static site files
          static/
          themes/
          hugo.yml
          README.md
$ hugo server --disableFastRender -D
# Press Ctrl + C to stop Hugo’s development server.
```

### Add content

```bash
hugo new content/posts/draft.md
```

### Configure your site

Start Hugo’s development server

```bash
hugo server -D # http://localhost:1313/
```

### Publish the site

Hugo creates the entire static site in the public directory in the root of your project.

```bash
hugo
rsync -avP public/* ${host}:/var/www/myblog.com/output/
```

## Reference

- <https://github.com/gohugoio/hugo>
- <https://github.com/adityatelange/hugo-PaperMod>
