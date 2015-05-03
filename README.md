# My blog http://achmad.in

This is based on [jekyll now](http://jekyllnow.com) and [lanyon](https://github.com/poole/lanyon) adaptation.
 
While tinkering with `jekyll serve` to develop locally by trying this and that tutorial, it turn out that I use `connect` module from node while leveraging livereload.
After some experiments, I decided to split the job between livereload that need to watch file modification on one shell 
and the other shell executing `jekyll build -w` to continuously build the jekyll site. That was the fastest *live editing* so far.