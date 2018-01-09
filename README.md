# wpCoffeeShop
Using the Google Places API, this admin side WordPress plugin queries your browser for your location and displays the nearest coffee shop.

See a screenshot at: https://suwdo.com/2017/02/wpcoffeeshop/

## Requirements

1. WordPress version 4.9+
1. WordPress running in HTTPS (SSL)
1. Google Places API Key (see step 1 in installation for more details)

## Installation

1. Go to the [Google Places API](https://developers.google.com/places/web-service/) page and request an API key.
If you do not already have one, yYou will need to create a Google Developer account to do so.
    1. Keep the API key in a safe place
1. Clone this repository (or download from [releases](https://github.com/bing0fuel/wpCoffeeShop/releases) into
your `WP_ROOT/wp-content/plugins/` directory.
    1. Note that if you are unzipping the code from releases, you may need to create the `wp-coffeeshop` folder.
1. Install the plugin as usual via the WordPress admin panel.
1. Go to the wpCoffeeShop settings and add the key you got from step 1
1. Once this is done, your browser will ask you for your location. Allow this and you're good to go!

## License 

See LICENSE.txt
