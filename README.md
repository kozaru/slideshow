# Harp Slideshow

This is a template app for creating simple and stylish slide decks using HTML,
CSS, and Javascript. It's powered by the [Harp](http://harpjs.com) web server.

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Demo

[harp-slideshow-template.herokuapp.com](http://harp-slideshow-template.herokuapp.com/)

## Run it Locally

If you don't already have node installed, [go to nodejs.org](http://nodejs.org/)
and click "Install". Easy peasy.

```sh
# Install Harp
npm install harp --global

# Install browser-sync
npm install browser-sync --global

# Download this repo as your harp boilerplate
harp init myshow --boilerplate kozaru/slideshow

# npm package install
npm install

# Run the server
harp server myshow

# Run LiveReload (other tab in terminal)
npm start
```

## License

MIT
