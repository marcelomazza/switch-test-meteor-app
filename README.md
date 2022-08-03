# switch-test-meteor-app

## Setup

Since this is just a test I'm compiling scss stylesheets from the command line:

```
sass --watch src/scss/index.scss style.css --style=compressed
```

Check the [Sass cli docs](https://sass-lang.com/documentation/cli/dart-sass)
for additional options.


## Notes

- Webfont implementation is lousy, ideally the font-weight should be handled by the property, not the additional font family. I implemented it this way to cut corners.