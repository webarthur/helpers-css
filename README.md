# [Helpers CSS Framework](http://helpers.araujo.cc)
Useful tools for web development.

Documentation: http://helpers.araujo.cc

## How to:

Helpers CSS uses basically six different types of HTML attributes:

```html
Text: <span text="bold italic blue">lorem ipsum</span>

Layout: <div layout="left absolute z-10">lorem ipsum</div>

Devices: <img
            on-mobile="no-float"
            on-tablet="left"
            on-netbook="right"
            on-desktop="hidden" />

Printer: <hr on-print="hidden" />

Columns: <div cols="3"> [...] </div>

Grid: <div grid="5"> [...] </div>
```

**Helpers CSS** can help you to remove repetition and leave the classes just for specific elements cofiguration. It's based on *HTML6*, *DRY* and *SMACSS* methodologies and compiled with SASS. The helpers attributes will definitely help you scale your code.

It's easy to use, simple and scalable.

### Example:

```html
<p text="gray-80 normal center">
  <span text="bold big line-1 red">
    Can you
  </span> feel the
  <span text="underline italic blue semi-bold">
    future
  </span>? HTML6
  <span text="pre white-80 line-1.5" layout="navy few-rounded inline-block">  advantages  </span>
   are expecting for
   <span text="bolder">you</span>!
</p>
```

## [Documentation](http://helpers.araujo.cc)

The framework's documentation was included in this repo in the root directory, search for index.html file. The docs may also be run locally.

* [Text](http://helpers.araujo.cc/#text)
* [Layout](http://helpers.araujo.cc/#layout)
* [Mobile/Printer](http://helpers.araujo.cc/#mobile)

## [Author](http://araujo.cc)

* [Arthur Araújo](http://araujo.cc)

## [Creative Commons License](http://creativecommons.org/licenses/by-sa/4.0/)

Code released under Creative Commons Share-alike, so Helpers CSS is absolutely free. It's open-source: you can copy, merge, publish and distribute the framework without any limitations! =D

<i>"Simplicity is the ultimate sophistication" - Leonardo da Vinci</i>
