# Uggly Boots

For this assignment, you'll be taking our modified Ugly Webby project and making it Uggly using Bootstrap components!


### Your Mission

Change as many components to Bootstrap components as you can!


### Basic Setup

* This is a `fork`-and-`clone` situation.


### Boostrap Setup

* Download Bootstrap's CSS file. Go to [their download page](https://getbootstrap.com/docs/4.4/getting-started/download/) and click the first download link (under "Compiled CSS and JS").
* This may give you a file you need to decompress. If so... do that thing!
* Then move the `bootstrap.css` file to your repo. You don't need any other files!
* Now to get Bootstrap in there, add a `link` tag under the one for `style.css`, and set its `href` property to be `bootstrap.css`.
* BAM. You should now see the "Uggly Boots" Component become much better-looking! If you weren't running Live Server, do that now and remove the `link` tag to see it get uglier again. Then add it back in to see it get Ugglier again!


### Modifying Your Bootstrappings

If you want to, you can override any of Bootsrap's components to add your own personal touch. Because it's all just straight CSS, any CSS you add after it will take precedence. It won't erase all of Bootstrap's CSS for that class, either; just the properties you want to change. Want to overwrite the font size of Bootstrap's `btn` class? Just add this to your `style.css` file:
```css
.btn {
  font-size: 1.5em;
}
```

As long as your CSS is loaded _after_ theirs, this will chagne that property of `btn` and that property alone. Cool, huh?


### Resources

Check out [Boostrap's component documentation](https://getbootstrap.com/docs/4.4/components/jumbotron/), it's got everything you could need to add whatever components you want to this thing!
