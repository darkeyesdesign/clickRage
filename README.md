# ButtonClick!
+ A simple, web-based, stress reliever
+ Alots 5 seconds for the aggravated/nervous user to click a huge, ass button as many times as possible.
+ Casual users need not log in or sign up, although their scores will not be persisted.

## Currently using:
+ [Compass](http://thesassway.com/beginner/getting-started-with-sass-and-compass) to organize CSS/SCSS
    ++ Dig into the functionality in `config.rb`
+ [Brunch](http://brunch.io/docs/getting-started) to build site
    ++ May hold off on using Brunch as I've never used it with MEAN and there may be a more appropriate 'builder'
+ Materialize to make Responsive

## Stack
+ Mongodb.Express.Angular.Node.

## File structure

`
darkeyesdesign/
|--node_modules/ (ignored)
|
|--materialize/ (ignored)
|--|--css/
|--|--fonts/
|--|--js/
|--|--LICENSE
|--|--README.md
|
|--sass/
|  |--partials/
|  |--|-- _base.scss
|  |--|-- _.scss
|  |--|-- _.scss
|  |
|  |--screen.scss (imports partials)
|
|--stylesheets/
|  |--...compiled css from screen.scss
|
|--media/
|--|--...images
|
|--js/
|--|--controllers/
|--|--directives/
|--|--app.js
|
|--config.rb
|--package.json
|--README.md
|--index.html`

### Version 2 prospect
+ Sights & sounds
+ User profile includes file upload