## Setup:

1. Clone this repo
2. Copy the SCSS directory to your project
3. Add this to the webpages:
```
    <header>
      <input type="checkbox" id="menu" />
      <!--   Hamburger button | Changes check state of input-->
      <label for="menu"><span></span></label>
      <nav>
        <ul>
          <!-- Image here -->
          <div>
            <li><a href="#">1st Link</a></li>
            <li><a href="#">2nd Link</a></li>
            <li><a href="#">3rd Link</a></li>
            <li><a href="#">Nth Link</a></li>
            <!-- More anchor elements inside of list items here -->
          </div>
        </ul>
      </nav>
      <div></div>
      <hr>
    </header>
```
4. Modify the links to your needs, you may add as many links as you like
5. Modify master.scss in the scss directory to your needs
5. Compile the SCSS to CSS and link the compiled CSS to your webpages

### Choosing different styles:

You can change the look of the menu easily, \
 have a look at master.scss in the SCSS directory and then compile it.

### Default and custom desktop layout:

To disable the default desktop layout comment this from master.scss and then compile:

    @use "./nav_desktop";

### I can't compile SCSS what should I do?
→ Use the CSS directory with the all the setups \
  then link to one of the stylesheets in there.

### Why should I use this?

→ It's quick and easy, requires the bare minimum of effort to set up.

Also see master.scss in the scss directory.
