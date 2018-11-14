# Connie's Personal Website

Connie Tang's VCG Capstone FA18 Project

## Description
Hellp! This contains my portfolio that includes my interests, resume, contact information, and projects. This repo is essentially an easy-to-customize personal dev portfolio that was created with Sass and JavaScript. It is lightweight and fully responsive, as well as comes with the Bootstrap grid system and loaded with Font Awesome. 


| #  | Description          | Hours Estimated | Completion Date | Notes |
| - | --------------------  | --------------- | --------------- | ----- |
| 1 | Look and implement a website template  | 3               | 11/1/2018       | something simplistic, clean, and elegant  | 
| 2 | Change the cover photo             | 1               | 11/2/2018       | Look for a nice HD professional background from Unsplash | 
| 3 | About Me Page         | 3               | 11/5/2018      | Contains my background and most recent work |
| 4 | Projects Page         | 3               | 11/7/2018      | Update the website template to have my CS projects and side work | 
| 5 | Site Tracker           | 3               | 11/13/2018      | Implement a way to track the IP addresses of people who click on various links in my website | 
| 6 | Purchase Website      | 1               | 11/14/2018      |      |

### Using The Template As Is

If you wish to use the template as is (i.e. how it's seen in the demo), then all that's required is the `css`, `images`, `js`, `libs` folders and the `index.html` file. You would then add your content to `index.html` as needed and you're good to go!

## Customization and Editing

### General

In general, most styles on the page are based off the definitions of variables in the variable section of the style sheet:

```SCSS
// Define base and accent colors
$base-color: #3498db;
$base-color-hover: darken($base-color, 10%);

// Define background colors
$background: #fff;
$background-alt: #f2f2f5;

// Define border colors
$border: #dcd9d9;

// Define text colors
$heading: #374054;
$text: #74808a;
```

If you wish to change the general colour scheme of the page for example, simply change the value of `$base-color`.

There is also a number of default CSS classes that can be applied such as `.shadow`, `.shadow-large`, `.btn-rounded-white`, and various others. These can be found under the General Styles section in the style sheet.

### Images

By default, the template comes with a number of images, some of which can be kept and others which act simply as placeholders and should be switched. The template contains the following:

* Main background (images/lead-bg.jpg) - this is the main background image provided via [Unsplash](https://unsplash.com/). This can be kept or changed easily by replacing `images/lead-bg.jpg` with your new background (recommended size of at least 1920x1080).
* Favicon (/favicon.ico) - this is the favicon used for the page. Similar to the main bg, this can kept or changed easily by replacing the `favicon.ico` with your new one.
* Project image - these are the images associated with the projects under the project section. These are simply placeholders and should either be replaced or removed.

## Technical 
 - Gulp ready (compiles Sass and minifies JS)
 - Sass ready with lots of commenting
 - Fully responsive
 - Comes with Bootstrap grid system
 - Easy colour changes can be done through simple variable edits

## Implementation 
Uploading the website template from Github: https://github.com/RyanFitzgerald/devportfolio
