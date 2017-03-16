# jekyllinfo

The Nuts and bolts for a system that allows you to view an info page
for your Jekyll site. This idea is shamelessly ripped off from the page
created by PHP's `phpinfo()` function.

To use, copy the files in this git repo to the appropriate directories
in your Jekyll source tree. Then point your browser at

<http://localhost:4000/jekyllinfo.html>

and the page will show some info about your site.

The standard theme in `css/jinfo.css` is ripped off from the design
of [jekyllrb.com][jekyllrb]. If you prefer the php-like theme instead,
you need to edit the file `_layouts/jinfo.html` and in the CSS stylesheet link
replace `jinfo.css` with a reference to the
`jinfo-css.css` [file][^1].

**You should remove these files from the production site.**

[jekyllrb]: http://jekyllrb.com/
[^1]: CSS shamelessly ripped off from the `phpinfo()` page
