![dragon](https://user-images.githubusercontent.com/20080981/125921861-8e43b043-527a-44c2-a31f-efdff097427a.png)

# DRAGON CSS FRAMEWORK π€
Take flight with Dragon today! 

# NEW AND IMPROVED π
This is version 2.0 of the original 'dragon-css' and in order to live up to it's name it needed some serious upgrades. For starters: We are now using SCSS to quickly compile a large amount of css code from a simpler, quicker to write .scss file. Another exciting new upgrade is the availability of fine tuning in all colours, margins, borders and padding, for instance: The colours have 49 levels of shading (0 - brightest, 49 - darkest). NOTE: If you want to use level 0 colour shading you will have to omit the '-0' from the end of the colour (e.g. 'primary-37' => 'primary-37', 'primary-0 => 'primary'). 

# CURRENTLY SUPPORTED FEATURES π€
- GRID
  - π¦ class='container' - Now using flexbox to stablize and extend our capabilities.
  - π£ class='row' - Pretty much the same as before π¬ just contains and keeps the columns in check β
  - π class='col-[size]' - 12 column grid system.
  -  πclass='off-[size]' - up to 11 columns of offset towards the right of the row.

- COLOURS (REMINDER: The brightest possible shade has no '-[shading level]' at the end just '[colour]')
  - π class='primary-[shading level (1 - 49)]'
  - π€ class='secondary-[shading level (1 - 49)]'
  - π class='warning-[shading level (1 - 49)]'
  - π class='error-[shading level (1 - 49)]' 
  - π class='highlight-[shading level (1 - 49)]' 
  - π€ class='light-[shading level (1 - 49)]' 
  - π€ class='dark-[shading level (1 - 49)]'

- UTILITY
  - β₯β€ class='w-[size (1-100)]' - change the width of an element
  - β₯β€ class='h-[size (1-100)]' - change the height of an element
  
  - π class='m-[size (1-100)]' - change the margin on all sides of an element
  - π class='mt-[size (1-100)]' - change the margin on the top of an element
  - π class='mr-[size (1-100)]' - change the margin on the right of an element
  - π class='mb-[size (1-100)]' - change the margin on the bottom of an element
  - π class='ml-[size (1-100)]' - change the margin on the left of an element
  - π class='mx-[size (1-100)]' - change the horizontal margin of an element
  - π class='my-[size (1-100)]' - change the vertical margin of an element
  
  - βοΈ class='p-[size (1-100)]' - change the padding on all sides of an element
  - βοΈ class='pt-[size (1-100)]' - change the padding on the top of an element
  - βοΈ class='pr-[size (1-100)]' - change the margin on the right of an element
  - βοΈ class='pb-[size (1-100)]' - change the margin on the bottom of an element
  - βοΈ class='pl-[size (1-100)]' - change the margin on the left of an element
  - βοΈ class='px-[size (1-100)]' - change the horizontal padding of an element
  - βοΈ class='py-[size (1-100)]' - change the vertical padding of an element

  - βοΈ class='box-shadow-[side (top, right, bottom, left)]' - add a soft shadow to an element on what ever side you want (omit the '-[side]' to get a shadow all the way around)
  - βοΈ class='box-shadow-[side (top, right, bottom, left)]-[strength]' - add a '-[strength (hard, solid)]' to make the standard shadow have less blur

  - βοΈ class='text-shadow-[side (top, right, bottom, left)]' - add a soft shadow to text on what ever side you want (omit the '-[side]' to get a shadow all the way around)
  - βοΈ class='text-shadow-[side (top, right, bottom, left)]-[strength]' - add a '-[strength (hard, solid)]' to make the standard shadow have less blur

  - π« class='unselectable' - Makes any text under the element this class is on unable to be selected by a user

- COMPONENTS
  - NAVBAR 
    - π class='navbar' - New and improved navbar component, now more responsive!
    - π class='nav-heading' - The title of the site goes here π
    - π class='nav-menu' - This magical class will contain the of the menu items in your navbar
    - π² class='nav-item' - This informs the framework that you are about to add a navigation item such as a link, button or input field
    - π class='nav-button' - To be fair you could use the standard 'button' but this one is specially tailored to look perfect on all devices so be careful β οΈ
    - π class='nav-link' - Creates a responsive link element in the navigation menu in the navbar 
    - π€ class='nav-search' - Creates a responsive input field to be used for whatever you like!
  - HERO
    - β‘οΈ class='hero' - A big section you can use on your pages to display some information
    - π§? class='hero-img' - A custom crafted image component that responds to different device sizes!
    - π class='hero-info' - This will contain all info items you want to put into your hero!
    - π class-'hero-subject' - The subject of your hero, be creative here :)
    - π class='hero-description' - Describe what you want your users to be aware of here
    - πΉ class='hero-button' - This is another custom button situation like the 'nav-button'
  - SPINNER
    - β­οΈ class='spinner-[size (1 - 5)]' - Use this custom css spinner to show your users when something is loading

# INSTALLATION
To install the latest version of Dragon include a stylesheet link to https://cdn.jsdelivr.net/gh/Connor-Walden/dragoncss/css-dist/dragon.min.css in your head and hack away!

# SHOWCASE
https://connor-walden.github.io/dragoncss/

# BUILT WITH
- HTML
- CSS
- SCSS
- Live SASS Compiler extension for vs code.
- css-minify npm package (available via npm install css-minify)

Thanks everyone <3
