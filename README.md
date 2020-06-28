# Bootstrap 5 Experiments

Checking out how the new bootstrap 5 library is.


## Using npm to package dependencies

> npm init -y
(-y : yes for all defaults)

Installing Bootstrap.
> npm i bootstrap@5.0.0-alpha1

Installing popper js.
> npm i popper.js
Popper js is for TOOLTIP & POPOVER POSITIONING ENGINE.

Installing Parcel 
> npm install -g parcel-bundler
Parcel is alternative of webpack a lightweight version.
Parcel is a web application bundler, differentiated by its developer experience. It offers blazing fast performance utilizing multicore processing, and requires zero configuration.

## Running the project

To Run the project:
> parcel index.html
(notice: this cannot be run in IDE terminal, external cmd is needed)


## Using Scss

In visual code, install "Live SASS Compiler" extension.
Click on a scss file and click on "watch sass" at the bottom of the IDE (in blue container).
This creates css and css.map file automatically.

## Documentation

Official Documentation
https://v5.getbootstrap.com/docs/5.0/getting-started/introduction/

Tutorial Documentation
https://mdbootstrap.com/docs/standard/


### Reference
Tutorial : https://www.youtube.com/watch?v=6lsJliBnUfM



## How to work with this project

We import the bootstrap scss in main.scss.

We can change variable like ($body-bg) and this will reflect automatically.

We can create utility classes with help of Utitlity API. We can configure class values like w-10 has width 10% using sass notation.

