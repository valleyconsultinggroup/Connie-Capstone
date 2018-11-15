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

### Optional Sections

The template comes with an optional section that can be added to the page markup to list things like Certifications, Hobbies, and more (Note: these are not included by default). The markup for the additional optional section is as follows:

```HTML
<div class="optional-section background-alt">
    <h2 class="heading">Section Name</h2>

    <div class="optional-section-block">
        <h3>Some content title</h3>
        <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur in iaculis ex. Etiam volutpat laoreet urna. Morbi ut tortor nec nulla commodo malesuada sit amet vel lacus. Fusce eget efficitur libero. Morbi dapibus porta quam laoreet placerat.
        </p>
        <ul>
            <li>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            </li>
            <li>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            </li>
            <li>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
            </li>
        </ul>
    </div>
    <!-- End .optional-section-block -->

</div>
<!-- End .optional-section -->
```

You can copy .optional-section-block for each new item you wish you have in the optional section. Also, the background-alt class may need to be removed depending on where the optional section is placed in your layout as this adds the grey background. If you play it at the bottom after "Skills", it can be used as is. Also, by default the border is applied at the top, but this can also be adjusted as needed.

The optional section blocks have styling for h3 (the block title), h4, p, and ul tags by default.


## Technical 
 - Gulp ready (compiles Sass and minifies JS)
 - Sass ready with lots of commenting
 - Fully responsive
 - Comes with Bootstrap grid system
 - Easy colour changes can be done through simple variable edits


## Implementation 
Uploading the website template from Github: https://github.com/RyanFitzgerald/devportfolio

