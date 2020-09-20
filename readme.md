# TooSlides


A project showing how to create a simple javascript plugin

## Getting Started

Get started by downloading the content of this repo. There are two main files of concern: `tooSlide.js` and `tooSlide.css`.

Link both files to the page where you want a slider:

`<link rel="stylesheet" href="tooSlide.css">`
`<script src="tooSlide.js`>

## Using the plugin

The plugin works by converting a list of images on a page to a slider.

### Steps
1 Create a container element that will house all sliding images e.g `<div class="sliderContainer"></div>`

2 Inside the container, add a new div for each image to be used e.g `<div class="singleSlide"><img src="path-to-image"></div>`

3 Initialize the plugin

```
var slider = new TooSlides({
    container: ".sliderContainer", // the classname of the overall parent 
    container
    slidesClass: ".singleSlide", //The classname of the sub container
    nextButton: ".next",
    previousButton: ".prev"
})
```

## License

TooSlides is open source software [licensed as MIT][license].