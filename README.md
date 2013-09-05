# Ribbon.css

Ribbon.css is a small css file which allows you to create awesome looking ribbons. **And without using any image!**

http://sw.cow.tc/ribbon.css

## Usage

The only requirement is the usage of [SCSS](http://sass-lang.com/). Once imported, Ribbon.css add the `ribbon` mixin which you can use in your stylesheets.

## Example

##### Markup

~~~ html
<html>
  <head>
    <title>Example</title>
    <link rel="stylesheet" type="text/css" href="style.css"/>
  </head>
  <body>
    <div class="ribbon">
      <a href="#">Awesome!</a>
    </div>
  </body>
</html>
~~~

##### Stylesheet

~~~ scss
// ... other imports before ...
@import "ribbon";
// ... other imports after ...

// ... other rules ...

.ribbon{
  @include ribbon;

  // Customize the A and SPAN here
}

// ... other rules ...
~~~

**That's it.** Pretty easy, isn' it?

## Browser compatibility

Tested to be working on Chrome 6+, Safari 4+, Firefox 3.6+, Opera 12+ and IE 9+.

## Contributing to ribbon.css

* Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
* Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
* Fork the project.
* Start a feature/bugfix branch.
* Commit and push until you are happy with your contribution.
* Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
* Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

## Copyright

Copyright (C) 2013 and above Shogun (shogun@cowtech.it).

Licensed under the MIT license, which can be found at http://www.opensource.org/licenses/mit-license.php.
