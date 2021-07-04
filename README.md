# Static Site
This is a bootstrap project to enable static site hosting on Heroku using the following build pack https://github.com/heroku/heroku-buildpack-static

## What you need
1. A Heroku account free or pay.
2. Create new app in Heroku.
3. On [Heroku App's setting tab] ex: https://dashboard.heroku.com/apps/{YourAppName}/settings click "Add buildpack" then enter "https://github.com/heroku/heroku-buildpack-static" to add it.
4. Visit the above [github buildpack project](https://github.com/heroku/heroku-buildpack-static) to learn more on how it work. But it quite simple. I only added 2 requirements to this app; "static.json" and "public_html/" dir as root for my content. That is sufficient to allow the buildpack to build and deploy.
5. Add heroku git remote using this command "git remote add heroku https://git.heroku.com/{YourAppName}.git"
6. Everytime you run "git push heroku master" Heroku will automatically build and deploy this repo.