# ribbon.css

## END OF DEVELOPMENT NOTICE - This package has been discontinued

Ribbon.css is a small SASS file which allows you to create awesome looking ribbons. **And without using any image!**

## Usage

The only requirement is the usage of [SASS](http://sass-lang.com/). Once imported, Ribbon.css add the `ribbon` mixin which you can use in your stylesheets.

Optionally you can import it by using [NPM](https://npmjs.com):

```
npm install ribbon.css
```

## Example

##### Markup

```html
<html>
  <head>
    <title>Example</title>
    <link rel="stylesheet" type="text/css" href="style.css" />
  </head>
  <body>
    <div class="ribbon">
      <a href="#">Awesome!</a>
    </div>
  </body>
</html>
```

##### Stylesheet

```scss
// ... other imports before ...
@import './ribbon';
// ... other imports after ...

// ... other rules ...

.ribbon {
  @include ribbon(top-left); // Supported placements are: top-left, top-right, bottom-left and bottom-right

  // Customize the inner contents
}

// ... other rules ...
```

**That's it!** Pretty easy, isn't it?

## Browser compatibility

Tested to be working on the most recent (that is: latest two major versions) of all modern browsers.

## Contributing to ribbon.css

- Check out the latest master to make sure the feature hasn't been implemented or the bug hasn't been fixed yet.
- Check out the issue tracker to make sure someone already hasn't requested it and/or contributed it.
- Fork the project.
- Start a feature/bugfix branch.
- Commit and push until you are happy with your contribution.
- Make sure to add tests for it. This is important so I don't break it in a future version unintentionally.
- Please try not to mess with the Rakefile, version, or history. If you want to have your own version, or is otherwise necessary, that is fine, but please isolate to its own commit so I can cherry-pick around it.

## Copyright

Copyright (C) 2013 and above Shogun (shogun@cowtech.it).

Licensed under the MIT license, which can be found at https://choosealicense.com/licenses/mit.
