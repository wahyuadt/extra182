Location: Home
Time: 7-9

1. Has fixed the problems with github pages using Index.md while local jekyll is using Readme.md

   The problems occured because i have an index.md files and the github page automatically choose
   index.md instead of readme.md, so i deleted the index.md and add this to the Gemfile
	
	gem 'jekyll-readme-index'

   which automatically assign readme as index.md




![img](https://github.com/wahyuadt/extra182/blob/master/_posts/img/Sketch2.png)

2. The theme is still hasn't fixed yet (the theme: in the _config.yml is not finding remote theme)

fixing soon.