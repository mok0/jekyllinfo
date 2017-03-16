# jekyllinfo

The Nuts and bolts for a system that allows you to view an info page
for you Jekyll site. This idea is shamelessly ripped off from the page
created by the `phpinfo()` function.

To use, copy the files in the git repo to the appropriate directories
in your Jekyll source tree. Then point your browser at

<http://localhost:4000/jekyllinfo.html>

The standard theme in `css/jinfo.css` is ripped off from the design
of [jekyllrb.com][jekyllrb]. If you prefer the php-like theme instead,
you need to edit the file `_layouts/jinfo.html` and in the CSS link
replace `jinfo.css` with a reference to the
`jinfo-css.css` [file][^1].

You probably should remove these files from the production site.

[jekyllrb]: http://jekyllrb.com/
[^1]: CSS shamelessly ripped off from the `phpinfo()` page
