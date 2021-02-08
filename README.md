# Forbidden Attack Lab

The hacking lab for Forbidden Attack in GCM mode

## Let Play

Please find a bud in the [app.py](/app.py) file. Then, hack this lab on your own environment. Next, get a real flag [https://forbidden-attack-lab.herokuapp.com/](https:/forbidden-attack-lab.herokuapp.com/). Finally, submit flag on [https://lab.suam.wtf/](https://lab.suam.wtf/).

## Running Locally

Make sure you have Python 3.7 [installed locally](http://install.python-guide.org). To push to Heroku, you'll need to install the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli).

```sh
$ git clone https://github.com/suam-team/forbidden-attack-lab.git
$ cd forbidden-attack-lab
$ pip install -r requirements.txt
$ echo "FLAG=flag{ILoveYou}" > .env
$ heroku local
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```sh
$ heroku create
$ git push heroku main
$ heroku open
```
or

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)
