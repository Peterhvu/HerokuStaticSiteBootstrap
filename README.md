# Static Site
This site is build using https://github.com/heroku/heroku-buildpack-static

On [Heroku App's setting tab](https://dashboard.heroku.com/apps/b042cd95-c1ac-41b8-bf3d-d63f01/settings) click "Add buildpack" then enter the github url above to add it.

Visit github buildpack project to learn more on how it work.

It quite simple. I added 2 requirements to this app; "static.json" and "public_html/" dir as root for content. This is sufficient to allow the buildpack to build and deploy.