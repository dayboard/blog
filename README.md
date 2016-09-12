# Dayboard's Blog

## Workflow for updating blog

Branch `gh-pages` is what the live blog lives

Branch `master` is where we push any blog updates staged to go live

Make branches when you're working on new posts so then we're not running into conflicts using the same branch.

E.g. Create branch off `master` as `archive_tasks`

Once it's ready to go live, follow instructions to Publish Drafts Live below, create new pull request, and we'll merge to `master`, then to `gh-pages`.

## Working with Drafts in Jekyll

Drafts are posts without a date. They’re posts you’re still working on and don’t want to publish yet. They are created in the **_drafts** folder, then using formula to name the file : title.md or title.html

To preview your site with drafts,

run `bundle exec jekyll serve --drafts`

Go to `localhost:4000/`

## Publishing drafts live in Jekyll

When you’re ready to publish you simply move the file to the **_posts** folder and rename it to include the current date.

E.g. `YYYY-MM-DD-title.md` or `YYYY-MM-DD-title.html`

