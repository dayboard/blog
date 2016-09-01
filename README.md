# Dayboard's Blog

# Working with Drafts in Jekyll

Drafts are posts without a date. They’re posts you’re still working on and don’t want to publish yet. They are created in the #_drafts# folder, then using formula to name the file : title.md or title.html

To preview your site with drafts, simply run #jekyll serve# or #jekyll build# with the #--drafts# switch. Each will be assigned the value modification time of the draft file for its date, and thus you will see currently edited drafts as the latest posts.

# Publishing drafts live in Jekyll

When you’re ready to publish you simply move the file to the #_posts# folder and rename it to include the current date.

E.g. YYYY-MM-DD-title.md or .html