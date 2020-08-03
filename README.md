## :earth_africa:Homepage url： 
```
https://hi.1tyu.com
```


## :turtle: Usage :turtle:

**Note:** If you're not familiar with Jekyll, please read up on [Jekyll's documentation](http://jekyllrb.com/) first.

and then run:

```
bundle install
```

...which installs `github-pages` gem. After that, run the server:

```
jekyll serve --watch
```

### Required

You **should** change these files before deploying:

* `_config.yml`: You must change `baseurl`, `url`, and `title`. Others are optional.
  * Make sure to restart the server after you update `_config.yml`.
* `CNAME`: Change this to host Shiori on a custom domain.
* `README.md`: Write your own README!
* `_includes/nav.html`: Modify or remove navigation links.
* `_includes/nav-right.html`: Modify or remove navigation links.
* `_includes/author_bar.html`: Customize the side bar.
* `_includes/post-header.html`: Customize the post header.
* `_includes/post-footer.html`: Customize the post footer.
* `_includes/footer.html`: Add copyright info, etc.

### Optional

You **may** customize these files - they're optional:

* `favicon.ico`: Favicon.
* `about.html`: About page. Currently not linked from anywhere.
* `_includes/head.html`: Extra stuff in the `<head>` tag.
* `_includes/scripts.html`: Extra stuff before the `</body>` tag.
* `_includes/post-header-home.html`: Customize the post header on the home page.

### Customize the Theme

To change my color theme, edit `_data/theme.yml`.

### Add Your Own CSS

You can customize CSS by editing these files:

* `_sass/custom-bootstrap-variables.scss`: Change Bootstrap variables ([documentation](http://getbootstrap.com/customize)).
* `_sass/custom-scss.scss`: Add your own custom CSS.

### Category Pages

If you want to make category pages, you must manually push the generated `_site` directory to GitHub. If you're still okay with that, [@alextsui05](https://github.com/alextsui05) made an [excellent demo and tutorial for category pages](http://alextsui05.github.io/shiori/categories-in-shiori/). You can see his code on [this pull request](https://github.com/ellekasai/shiori/pull/11).

## :turtle: License :turtle:


[MIT License](http://ellekasai.mit-license.org/)
