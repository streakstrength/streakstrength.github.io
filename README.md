# streakstrength.github.io

A website for professional teaching portfolio and reflection. 
© 2018 Sarah Tan Ruiqi. All rights reserved.

Structure: 
+-- index.html - initiates site

+-- \_config.yml - contains information e.g. name, markdown language, permalink of posts

+-- README.md (this doc)
+-- .gitignore - ignores \_site directory that Jekyll automatically creates for each commit
+-- css
    +-- main.css - controls the main font and styling attributes 
+-- \_includes
    +-- collect_tag.html - collects a list of site.tags (see: http://longqian.me/2017/02/09/github-jekyll-tag/) 
    +-- head.html - executes collect_tag.html when Jekyll header is defined
+-- \_layouts
    +-- dateless.html - used on dateless pages e.g. About page
    +-- default.html - default template
    +-- post.html - used for posts e.g. in Teaching Philosophy, Geography etc. 
    +-- tag_page.html - used to generate posts with selected tags on pages
+-- \_posts - where all the posts are stored. NB: TITLE FORMAT: "YYYY-MM-DD-your-title-here.md"
+-- about
    +-- index.html
+-- blog
    +-- index.html
+-- css
    +-- index.html
+-- geog
    +-- index.html
