
[![birthday](http://i.imgur.com/8jr9txD.png)](#)

# `$ birthday`

 [![Patreon](https://img.shields.io/badge/Support%20me%20on-Patreon-%23e6461a.svg)][patreon] [![PayPal](https://img.shields.io/badge/%24-paypal-f39c12.svg)][paypal-donations] [![AMA](https://img.shields.io/badge/ask%20me-anything-1abc9c.svg)](https://github.com/IonicaBizau/ama) [![Travis](https://img.shields.io/travis/IonicaBizau/birthday.svg)](https://travis-ci.org/IonicaBizau/birthday/) [![Version](https://img.shields.io/npm/v/birthday.svg)](https://www.npmjs.com/package/birthday) [![Downloads](https://img.shields.io/npm/dt/birthday.svg)](https://www.npmjs.com/package/birthday) [![Get help on Codementor](https://cdn.codementor.io/badges/get_help_github.svg)](https://www.codementor.io/johnnyb?utm_source=github&utm_medium=button&utm_term=johnnyb&utm_campaign=github)

> Know when a friend's birthday is coming.

[![birthday](http://i.imgur.com/giMbOtY.png)](#)

## :cloud: Installation

You can install the package globally and use it as command line tool:


```sh
$ npm i -g birthday
```


Then, run `birthday --help` and see what the CLI tool can do.


```
$ birthday --help
Usage: birthday [options]

Options:
  -n, --name <name>           The person name.
  -d, --date <date>           The person birthday or born date.
  -c, --coming <date>         Comming birthdays. Pass a date in the future.
  -b, --birthday-path <path>  Use a different birthday json file path.
  -h, --help                  Displays this help.
  -v, --version               Displays version information.

Examples:
  birthday -n 'Ionică Bizău' -d '14/09/1995'
  birthday -n 'Ionică Bizău' -d '14/09'
  birthday -c '2015-10-10'
  birthday # displays all birthdays

Documentation can be found at https://github.com/IonicaBizau/birthday
```

## :clipboard: Example


Here is an example how to use this package as library. To install it locally, as library, you can do that using `npm`:

```sh
$ npm i --save birthday
```



```js
// Dependencies
var Birthday = require("birthday");

// Insert a new birthday
Birthday.insert({
    name: "Ionică Bizău"
  , born: new Date(1995, 9, 14)
});
```

## :memo: Documentation

For full API reference, see the [DOCUMENTATION.md][docs] file.

## :yum: How to contribute
Have an idea? Found a bug? See [how to contribute][contributing].


## :moneybag: Donations

Another way to support the development of my open-source modules is
to [set up a recurring donation, via Patreon][patreon]. :rocket:

[PayPal donations][paypal-donations] are appreciated too! Each dollar helps.

Thanks! :heart:


## :scroll: License

[MIT][license] © [Ionică Bizău][website]

[patreon]: https://www.patreon.com/ionicabizau
[paypal-donations]: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=RVXDDLKKLQRJW
[donate-now]: http://i.imgur.com/6cMbHOC.png

[license]: http://showalicense.com/?fullname=Ionic%C4%83%20Biz%C4%83u%20%3Cbizauionica%40gmail.com%3E%20(http%3A%2F%2Fionicabizau.net)&year=2015#license-mit
[website]: http://ionicabizau.net
[contributing]: /CONTRIBUTING.md
[docs]: /DOCUMENTATION.md
