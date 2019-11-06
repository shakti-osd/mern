$ git init
$ git add .
$ git commit -m "first commit"
$ git remote add origin https://github.com/shakti-osd/mern.git
$ git push -u origin master


$ git pull https://github.com/shakti-osd/mern.git


Heroku Migration

Install Heroku on Ubuntu
$ sudo snap install --classic heroku

If you haven't already, log in to your Heroku account and follow the prompts to create a new SSH public key.
$ heroku login
or
$ heroku login -i

Create heroku app
$ heroku create

Create a new Git repository
Initialize a git repository in a new or existing directory

$ cd my-project/
$ git init
$ heroku git:remote -a kinsii

Deploy your application
Commit your code to the repository and deploy it to Heroku using Git.

$ git add .
$ git commit -am "make it better"
$ git push heroku master

Existing Git repository
For existing repositories, simply add the heroku remote

$ heroku git:remote -a kinsii
