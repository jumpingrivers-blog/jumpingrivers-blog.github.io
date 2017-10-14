# README

Install the `blogdown` package

```
install.packages("blogdown")
```

  * Add `options(servr.daemon = TRUE)` to your `.Rprofile` to allow continuous updating
  * You can build the site via `blogdown::serve_site()`
  * Add your posts to `content/posts/201X`
    * Commit both `Rmd` and resulting `html` files
    * For drafts, add `drafts: true` in the yaml
    * Images go in `static/img/20XX`
 * [netlfy](https://tax-collector-jacinta-81460.netlify.com/) address
