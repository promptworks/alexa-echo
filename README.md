`alexa-echo`
========

`alexa-echo` provides a server for an example Alexa Skill that will echo whatever is said to it.

This repo is a companion repo to [our blog post on creating Alexa skills](http://prompt.works/blog/writing-skills-for-amazon-alexa).

## Running `alexa-echo` locally

Install requirements by running:

    pip install -r requirements.txt

Then, the API can be run with:

    gunicorn echo.app:app
