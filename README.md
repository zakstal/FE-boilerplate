# FE interview boilerplate

This boilerplate includes
- React
- Redux
- SASS
- Reselect
- Json server

## Startup

To start the application run
`npm install`
`npm start`

To start the JSON server run
`npm run json-server`


## JSON server

The JSON server includes two tables, one of cat images under `/cats` and one of dog images under `/dogs`.
The JSON server will run on port `3001`.


# The Project


You're making a site of your favorite type of animal (either a cat or dog obviously) and you want to display a grid of images where each image is centered with a 1:1 aspect ratio.

This grid needs to be responsive down to mobile.

Each image should have a click event that opens a modal and displays the image centered so you can admire each creature's glory.

The modal should be made by you and not utilize an external libraries (except React).
The modal should display full screen with a background overlay and the content centered in the viewport. Please add a nice entrance and exit animation.

Images for your favorite animal are available via JSON server.

You can add any additional flair to Your website as well as tests if you have time.
