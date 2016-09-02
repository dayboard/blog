# Dayboard's Blog

# Working with Drafts in Jekyll

Drafts are posts without a date. They’re posts you’re still working on and don’t want to publish yet. They are created in the #_drafts# folder, then using formula to name the file : title.md or title.html

To preview your site with drafts,

run #bundle exec jekyll serve --drafts#

Go to #localhost:4000/#

# Publishing drafts live in Jekyll

When you’re ready to publish you simply move the file to the #_posts# folder and rename it to include the current date.

E.g. YYYY-MM-DD-title.md or .html