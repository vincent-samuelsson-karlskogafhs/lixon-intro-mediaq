# lixon-intro-mediaq


### what is media queries

Media queries are a key part of responsive web design, as they allow you to create different layouts depending on the size of the viewport, but they can also be used to detect other things about the environment your site is running on, for example whether the user is using a touchscreen rather than a mouse

What is media queries?
Media queries in CSS are a way to apply styles to a web page based on the size of the given screen. We can have rather large screen, and we can also have a very small one, like a mobile phone. This is very useful for creating responsive web page designs that adapt to different screen and devices.

How to we do this then? Of course by using media queries.

Here us a basic example:

@media screen and (max-width: 600px) {
  /* Styles for screens with a maxiumum width of 600 pixels */

  nav {
    background-color: red;
  }
}
@media: this is the keyword that indicates the beginning of a media query.
screen: specifies that the styles within the media query should only apply to devices with screens. (not devices that might not have screen, like printers)
(max-width: 600px): this is the condition that must be true in order for the styles within the media query to be applied. In this case, the styles will only apply if the screen width is 600px or less.
There are many more ways you can specify your condition, but in the majority of cases we use max-width or something that is called min-width.

Standard Breakpoints - Media Queries
The size on the media query above as an arbitrary value that I just picked, but this is of course up to the developer to choose. There exists sort of standard values in the IT business, I say sort of because there are many variants. But the standard values are as follows according to the developing tools in Chrome:

4K: Screens larger than 2560px
Laptop L: Larger than 1440px
Laptop: larger than 1024px
Tablet: larger than 768px
Mobile L: larger than 425px
Mobile M: larger than 375px
Mobile S: larger than 320px