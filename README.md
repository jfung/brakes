Brakes
=========
*Super easy deployment for people that aren't ruby-friendly*

### How to:

1) Clone this repository:

    git clone git://github.com/rdnck76/brakes.git
2) Copy all of your files to the "public" directory

3) Update the index:

    git add .
4) Save your changes:

    git commit -am "YOUR MESSAGE HERE"

At this point you have two choices:

#### Option A: Set it up with Pliers (good if you're on Windows)

5) Create a Heroku account [here](https://api.heroku.com/signup)

6) Login to [Pliers](https://pliers.heroku.com) and create a new application (follow the steps there)

7) Send your changes to Heroku

    git push heroku master


#### Option B: Set it up through Heroku (good if you're on Linux)

5) Create a Heroku account [here](https://api.heroku.com/signup)

6) Install the Heroku gem ([click here for instructions](http://docs.heroku.com/heroku-command))

7) Create the application

    heroku create
8) Send your changes to Heroku

    git push heroku master

### Demo:
Check out brakes powering [brakes.grapepudding.com](http://brakes.grapepudding.com).

### Issues:

I use [github's issue tracker](http://github.com/rdnck76/brakes/issues).  If you find a bug, let me know or send me a pull request.  I'm usually pretty quick on merges.

### Contact Info:
Send me a message through github, or if you don't want to make an account, you can email me [here](http://www.google.com/recaptcha/mailhide/d?k=019VOY8sZpMAlsOi1rUb7h5w==&c=11YgbNIYIBV1qjUDhHdKEkjtNy7aEvAj4ivxy4l_hWg=). (you'll have to put up with a captcha, sorry).

### License:
© 2010 Nate Benes <http://grapepudding.com>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.