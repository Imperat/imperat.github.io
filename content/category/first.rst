Hello, World!
#################

:date: 2018-02-09 19:30

Hi, Amazing world. Today is Friday!

I want to write this article for myself to not forget the steps which I need use
to publish new pages with github pages and pelican.

Firstly it's needed to build the site:

`pelican content -o output -s pelicanconf.py`

Secondly it's needed to push the content of output directory into master branch:

`ghp-import output && git push origin gh-pages:master`

Also do not forget to commit changes into develop branch.