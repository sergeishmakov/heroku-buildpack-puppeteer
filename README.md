This was (manually) forked from 
[puppeteer-heroku-buildpack](https://github.com/jontewks/puppeteer-heroku-buildpack).
This fork adds support for more fonts.

Note that [this other fork](https://github.com/CoffeeAndCode/puppeteer-heroku-buildpack)
only adds support for a few fonts, and we need more.

# heroku-buildpack-puppeteer

Installs dependencies needed in order to run puppeteer on heroku. Be sure to include `{ args:
['--no-sandbox', '--disable-setuid-sandbox'] }` in your call to `puppeteer.launch`
