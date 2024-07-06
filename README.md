# SVN CSS Library 1.0

A simple and reusable CSS library for responsive web designs.

## Installation

Add the CSS file to your project by including it in your HTML file:

<link rel="stylesheet" href="path/to/svn.css">

## Usage

Apply the following CSS classes to your HTML elements to achieve the desired styles.

<div class="svn-container">
  <div class="svn-row">
    <div class="svn-col svn-col-lg-6">
      <p class="svn-bold-text svn-color-white">This is an example text.</p>
    </div>
    <div class="svn-col svn-col-lg-6">
      <img src="path/to/image.jpg" class="svn-img-res" alt="Example image">
    </div>
  </div>
</div>

## Classes

Basic Styles

	•	.svn-radius: Rounds the corners of an element.
	•	.svn-bold-text: Makes the text bold.
	•	.svn-icon: Sets the height of an icon to 35px.
	•	.svn-icon-s: Sets the height of a small icon to 25px.
	•	.svn-color-white: Makes the text white.
	•	.svn-m-top: Adds a 5px top margin.
	•	.svn-p: Adds a 10px padding.
	•	.svn-text-center: Centers the text.
	•	.svn-img-res: Makes an image responsive and centers it.

Layout

	•	.svn-container: Centers the content and adds padding.
	•	.svn-row: Creates a flex container for columns.
	•	.svn-col: Defines a column with padding.
	•	.svn-col-lg-*: Defines column widths for large screens (desktops).
	•	.svn-col-md-*: Defines column widths for medium screens (tablets).
	•	.svn-col-sm-*: Defines column widths for small screens (phones).

Animations

	•	.svn-btn: Adds a transform animation to a button.
	•	.svn-btn:hover: Enlarges the button on hover.

Contributing

Feel free to contribute to this library by submitting a pull request. Ensure your changes are well-documented and tested.
