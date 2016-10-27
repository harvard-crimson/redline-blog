# Redline
This is just a list of the articles we publish in the data blog. A simple jekyll site should suffice.

# Setup
[Install Jekyll](http://jekyllrb.com/docs/installation/). 
```
gem install jekyll
```
Clone the repository and enter it.
```
git clone https://github.com/harvard-crimson/redline.git
```
Start Jekyll.
```
jekyll serve
```
Navigate to `localhost:4000/overflow/`.

# Adding a new post
Create a new file in the `_posts` directory, following the naming scheme `YYYY-MM-DD-post-title.markdown`. Note that posts will appear in chronological order, and a post with a date later than today's date will not appear.

# Directory descripstions.

Resusable snippets of codes like the header, sidebar, footer go to _includes.
SCSS stylesheets go to _sass
Images, Data, Javascript files go to asset (please organize this section carefully)
