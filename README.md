# Adding a top level tab

* Create a file /path/to/repo/your-new-tab.html
* Add "your-new-tab" to templates list in index.html under "templating + routing," without the ".html"
* Add a navbar entry. href must be #!<name of your html file>: `<li><a href="#!your-new-tab" class="navbarlink">Your New Tab Name</a></li>`

# Adding a post

* Add entry to state.posts in index.html
* Add image for post in img/<id>.png
* Add actual post text in posts/<id>.html
