# Lazy Loading Nivo Slider

A fork of Nivo Slider enabling lazy loading of images. 

Use cases:

 * Dozens of images in the slideshow
 * Very large images
 * Mobile enviornments

## Usage

Works exactly like the existing Nivo Slider with one little change. Add a `data-src` attribute to your images:

Before:

  `<img src="my-image.jpg" alt="" title="Caption for my image.">`

After:

  `<img data-src="my-image.jpg" alt="" title="Caption for my image.">`

And that's it! Though it's highly recommended to include a `src` to placeholder image for valid HTML markup. 

View the live example: [http://powers1.net/files/nivo/demo/demo-lazy.html](http://powers1.net/files/nivo/demo/demo-lazy.html)

See `demo/demo-lazy.html` in the repository for example code. 

## About the author

Forked by Lee Powers: [http://powers1.net](http://powers1.net)

## About Nivo Slider

To find out more about Nivo Slider visit the home page at [http://nivo.dev7studios.com](http://nivo.dev7studios.com)

Nivo Slider GitHub Project Page: [https://github.com/ho-nl/Nivo-Slider](https://github.com/ho-nl/Nivo-Slider)

