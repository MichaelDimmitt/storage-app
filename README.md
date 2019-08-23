## Install instructions
You will need to ask me for the master key for this application 
<br/>to gain access to the aws bucket.
```bash
git clone https://github.com/MichaelDimmitt/storageapp.git
cd storageapp
rails s
```

## Order in which things are added to the project
1) ActiveStorage image uploading to an aws s3 bucket
2) Authenticaion (maybe simple solution or devise + omniauth.)
3) 

## Scaffold commands:
rails new storageapp
rails g resource comment content:text

## Additional useful commands:
bin/rails active_storage:install
bin/rails active_storage:install:migrations
bin/rails db:migrate

## Helpful resources for this application: (listed in order of most helpful to least helpful)
https://afreshcup.com/home/2017/07/23/activestorage-samples
https://medium.com/@wrburgess/a-comprehensive-list-of-activestorage-tutorials-for-rails-5-2-8ea7d4ea267e

https://guides.rubyonrails.org/active_storage_overview.html
