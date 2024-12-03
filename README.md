# General

This website uses github pages and jekyll and was created using the template from [al-folio]https://github.com/alshedivat/al-folio). Many of the features have not changed significantly and so for anything you are unsure about, that is an excellent resource!

The site can be run locally using docker. The command to beging serving the site is `docker compose up`. The site should then be available at `localhost:8080`.

Changes to the website should be pushed to `main` branch. There is then a github action setup to deploy changes to gh-pages branch from where the website is served.

# Blog

Blog posts should be in markdown format and added to `_posts` folder. Their name should be in the format YYYY-mm-dd-name-of-blog-post.md where the date is the date the post was published. 

# News

Similarly, news posts can be saved in `_news` folder. The name uses the same format but in this case it's only for organisation because date is an explicit parameter inside the file.

# People

New people can be added by appending them to `_pages/profiles.md`. By convention, the text for each person is stored in `_pages/about_name.md`. Images are stored in `assets/img` folder and should be sqaure aspect ratio.

# Projects

New projects can be added to the `_projects` folder.