# Wego

Lists hotel information obtained from hotel API endpoint. File is in ```/data/hotels.json```.

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) installed. Then run `polymer serve` to serve your application locally. Make sure your version of Polymer is Polymer 2.0

## Viewing Your Application

```
$ polymer serve

```

Preview page at ```127.0.0.1:8081/```.

## Structure

Main code is located at ```/src/Wego-app```. The main page is at ```wego-app.html```, and the star ratings component and score badge component are at ```rating.icon.html``` and ```score-badge.html``` respectively. Star ratings component and score badge component are built from scratch.

Styles for ```wego-app.html``` are located at ```/src/styles/styles.css```. Styles for the star ratings and score badge components are within the components themselves.

Assets for the star rating and for the different colored score badges (for the ratings: 'Good', 'Poor', 'Fair') are at the ```/assets``` directory.

### Libraries used
1. [iron-ajax](https://www.webcomponents.org/element/PolymerElements/iron-ajax) is used for making requests.
2. [iron-image](https://www.webcomponents.org/element/PolymerElements/iron-image)
