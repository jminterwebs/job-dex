# README

Set up 
  - Make sure you have ruby 3.3.3 and rails 7 installed
  - bundle install
  - rails db:create db:migrate
  - setup secrets `bundle exec rails secret`
  - #VSCode `EDITOR='code --wait' rails credentials:edit`
    copy secret in as `devise_jwt_secret_key: key`
  - rails s

 Concept can be located [here](https://medium.com/@johnverdone/the-fun-of-looking-for-work-51b5e5a41ddc)

Todo:

- Fully Set up users model
- Contacts
- Jobs