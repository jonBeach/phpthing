# phpthing

To build this you need a server to run php files. Like heroku.
Download heroku tool belt. Download composer from getcomposer.org.
Make a heroku account and make a new github app.
Upload the php file to github along with a composer.json file with only "{ }" in it using git.
Then create a heroku app.
Then upload github project to heroku

Commands: 
git add .
git commit -m ""
git push
heroku create
git push heroku master