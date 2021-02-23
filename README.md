## Setup:

1. Clone this repo
2. Modify master.scss and _variables.scss from the scss directory to your needs
3. Add this to your webpages:
```
    <header>
      <input type="checkbox" id="menu" />
      <!--   Hamburger button | Changes check state of input-->
      <label for="menu"><span></span></label>
      <nav>
        <ul>
          <!-- Image/Logo here -->
          <div>
            <!-- Items (Links) -->
            <li><a href="#">1st Link</a></li>
            <li><a href="#">2nd Link</a></li>
            <li><a href="#">3rd Link</a></li>
            <li><a href="#">Nth Link</a></li>
            <li><a href="#">Nth Link</a></li>
            <li><a href="#">Last Link</a></li>
          </div>
        </ul>
      </nav>
      <div></div>
    </header>
```
4. Modify the links to your needs, you may add as many links as you like
6. Compile the SCSS to CSS and link the compiled CSS to your webpages

### Default and custom desktop layout:

To disable the default desktop layout comment this from master.scss and then compile:

    @use "./nav_desktop";

To make your own desktop layout please uncomment the following line:

    @use "./nav_custom";

Then put your desktop styles in _nav_custom.scss and compile.

### Why should I use this?

→ The setup is quick & easy

See master.scss and _variables.scss for more details.
