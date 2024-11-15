# Aurora

Learning Bootstrap from [a Youtube](https://www.youtube.com/watch?v=b9g4_8nAsdA&t=3228s) video 😊
Learning how to create responsive websites using Bootstrap. Bootstrap is a powerful, feature-packed frontend toolkit.

## About Bootstrap

### Components

Follow [Bootstrap website](https://getbootstrap.com/) for latest changes.

#### Built-in

When you add Bootstrap to your project you get built-in components from Bootstrap so you don't have to create them from scratch like buttons, nav bar, modal, forms, accordion, carousel.

#### Third party

If the Bootstrap components are not enough, you can use third party UI Kits and you can easily integrate them in your Bootstrap project.

### Utility Classes

To add quick styles for example adding font-size.

### Container

Containers are a fundamental building block of Bootstrap that contain, pad, and align your content within a given device or viewport.
Bootstrap comes with three different containers:

- container, which sets a max-width at each responsive breakpoint
- container-{breakpoint}, which is width: 100% until the specified breakpoint
- container-fluid, which is width: 100% at all breakpoints

### Grid System

Bootstrap’s grid system uses a series of containers, rows, and columns to layout and align content. It’s built with flexbox and is fully responsive. Each row has 12 columns.

### Responsiveness

Bootstrap is mobile-first and uses breakpoints to change layout at specific device sizes

- Components: All Bootstrap components are responsive out of the box.
- Utility classes: Can be changed in specific break points based on view port size.
- Typography: Typography will scale up or down based on the device size.

`You still maybe need to write custom CSS.`

### VSCode Extension

Install `HTML CSS Support` extension to add CSS intellisense to HTML.

### Installation

You can install Bootstrap in two different ways.

- Install via PackageManage (Source code (Sass)): The more proper way is to install Bootstrap using nodejs and npm. This way you have more control. You can access to the source code and modify it for your needs if you want. For example you can change primary color.
- Install via CDN (link): Simply adding Bootstrap CSS and JS links. To modify you can modify the link (but the CDN link is not legible as it is minified) to your custom stylesheet.

### Bootstrap Icons

Bootstrap also has icons that you can use in your project.

## About Website

A website to book tours. It is responsive and uses Bootstrap grid system and utility classes.

### Components

The built in Bootstrap components that the project uses are:

- Nav bar
- Carousel
- Modal
- Form with floating label
- Card
- Accordion
- Footer
- Button
