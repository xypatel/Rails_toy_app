# README

## Toy App

### Rails Version 6.1.3

To update Database:

`rails db:migrate`

### Heroku Deployement

`heroku create`

`git push heroku master`

If you get could not build bundle error when trying to deploy to heroku:

`bundle lock --add-platform x86_64-linux`
