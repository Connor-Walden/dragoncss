![dragon](https://user-images.githubusercontent.com/20080981/125921861-8e43b043-527a-44c2-a31f-efdff097427a.png)

# DRAGON CSS FRAMEWORK 🤑
Take flight with Dragon today! 

# NEW AND IMPROVED 😍
This is version 2.0 of the original 'dragon-css' and in order to live up to it's name it needed some serious upgrades. For starters: We are now using SCSS to quickly compile a large amount of css code from a simpler, quicker to write .scss file. Another exciting new upgrade is the availability of fine tuning in all colours, margins, borders and padding, for instance: The colours have 49 levels of shading (0 - brightest, 49 - darkest). NOTE: If you want to use level 0 colour shading you will have to omit the '-0' from the end of the colour (e.g. 'primary-37' => 'primary-37', 'primary-0 => 'primary'). 

# CURRENTLY SUPPORTED FEATURES 🤗
- GRID
  - 📦 class='container' - Now using flexbox to stablize and extend our capabilities.
  - 🚣 class='row' - Pretty much the same as before 😬
  - 🏛 class='col-[size]' - 12 column grid system.
  -  🏛class='off-[size]' - up to 11 columns of offset towards the right of the row.

- COLOURS (REMINDER: The brightest possible shade has no '-[shading level]' at the end just '[colour]')
  - 💙 class='primary-[shading level (1 - 49)]'
  - 🤎 class='secondary-[shading level (1 - 49)]'
  - 💛 class='warning-[shading level (1 - 49)]'
  - 💔 class='error-[shading level (1 - 49)]' 
  - 💚 class='highlight-[shading level (1 - 49)]' 
  - 🤍 class='light-[shading level (1 - 49)]' 
  - 🖤 class='dark-[shading level (1 - 49)]'

- UTILITY
  - ⇥⇤ class='w-[size (1-100)]' - change the width of an element
  - ⇥⇤ class='h-[size (1-100)]' - change the height of an element
  
  - 📖 class='m-[size (1-100)]' - change the margin on all sides of an element
  - 📖 class='mt-[size (1-100)]' - change the margin on the top of an element
  - 📖 class='mr-[size (1-100)]' - change the margin on the right of an element
  - 📖 class='mb-[size (1-100)]' - change the margin on the bottom of an element
  - 📖 class='ml-[size (1-100)]' - change the margin on the left of an element
  - 📖 class='mx-[size (1-100)]' - change the horizontal margin of an element
  - 📖 class='my-[size (1-100)]' - change the vertical margin of an element
  
  - ☁️ class='p-[size (1-100)]' - change the padding on all sides of an element
  - ☁️ class='pt-[size (1-100)]' - change the padding on the top of an element
  - ☁️ class='pr-[size (1-100)]' - change the margin on the right of an element
  - ☁️ class='pb-[size (1-100)]' - change the margin on the bottom of an element
  - ☁️ class='pl-[size (1-100)]' - change the margin on the left of an element
  - ☁️ class='px-[size (1-100)]' - change the horizontal padding of an element
  - ☁️ class='py-[size (1-100)]' - change the vertical padding of an element

  - ⛅️ class='box-shadow-[side (top, right, bottom, left)]' - add a soft shadow to an element on what ever side you want (omit the '-[side]' to get a shadow all the way around)
  - ⛅️ class='box-shadow-[side (top, right, bottom, left)]-[strength]' - add a '-[strength (hard, solid)]' to make the standard shadow have less blur

  - ⛅️ class='text-shadow-[side (top, right, bottom, left)]' - add a soft shadow to text on what ever side you want (omit the '-[side]' to get a shadow all the way around)
  - ⛅️ class='text-shadow-[side (top, right, bottom, left)]-[strength]' - add a '-[strength (hard, solid)]' to make the standard shadow have less blur

  - 🚫 class='unselectable' - Makes any text under the element this class is on unable to be selected by a user

- COMPONENTS
  - NAVBAR 
    - 🚁 class='navbar' - New and improved navbar component, now more responsive!
    - 👈 class='nav-heading' - The title of the site goes here 😄
    - 🗒 class='nav-menu' - This magical class will contain the of the menu items in your navbar
    - 📲 class='nav-item' - This informs the framework that you are about to add a navigation item such as a link, button or input field
    - 🔘 class='nav-button' - To be fair you could use the standard 'button' but this one is specially tailored to look perfect on all devices so be careful ⚠️
    - 🔗 class='nav-link' - Creates a responsive link element in the navigation menu in the navbar 
    - 👤 class='nav-search' - Creates a responsive input field to be used for whatever you like!
  - HERO
    - ⚡️ class='hero' - A big section you can use on your pages to display some information
    - 🧮 class='hero-img' - A custom crafted image component that responds to different device sizes!
    - 📊 class='hero-info' - This will contain all info items you want to put into your hero!
    - 📘 class-'hero-subject' - The subject of your hero, be creative here :)
    - 📜 class='hero-description' - Describe what you want your users to be aware of here
    - 🕹 class='hero-button' - This is another custom button situation like the 'nav-button'
  - SPINNER
    - ⭕️ class='spinner-[size (1 - 5)]' - Use this custom css spinner to show your users when something is loading

# INSTALLATION
To install the latest version of Dragon include a stylesheet link to https://cdn.jsdelivr.net/gh/Connor-Walden/dragoncss/css-dist/dragon.min.css in your head and hack away!

# BUILT WITH
- HTML
- CSS
- SCSS
- Live SASS Compiler extension for vs code.
- css-minify npm package (available via npm install css-minify)

Thanks everyone <3
