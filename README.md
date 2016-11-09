```
       ╭──────────────╮
       |              |
      /               |
     /   (    )       |
    /        _____ ___|__   ___   ____     ___      ______  __ __    ___  ___ ___    ___
   /        / ___/|      | /   \ |    \   /  _]    |      ||  |  |  /  _]|   |   |  /  _]
  /__      (   \_ |      ||     ||  _  | /  [_     |      ||  |  | /  [_ | _   _ | /  [_
    |       \__  ||_|  |_||  O  ||  |  ||    _]    |_|  |_||  _  ||    _]|  \_/  ||    _]
    |_      /  \ |  |  |  |     ||  |  ||   [_       |  |  |  |  ||   [_ |   |   ||   [_
     /      \    |  |  |  |     ||  |  ||     |      |  |  |  |  ||     ||   |   ||     |
    /        \___|  |__|   \___/ |__|__||_____|      |__|  |__|__||_____||___|___||_____|
   /                  | Responsive  admin theme for PyroCMS 3
  ╰───────────────────╯ 
```
> Built on the popular open source project [AdminLTE](https://almsaeedstudio.com/themes/AdminLTE/index2.html), this theme is easy to install and customize with a slick ui and intuitive user experience making PyroCMS a more pleasurable framework to work with.

## Install

In your project folder, require the theme package with `composer`,

```bash
composer require websemantics/stone-theme
```

Edit `.env` file and change the value of `ADMIN_THEME` to,

```
ADMIN_THEME=websemantics.theme.stone
```

## Customize

Stone theme is built with `less` and is easy to customize by changing themes variables in `resources/less/theme/variables.less`. 
A straightforward change is altering the theme primary color which would reflect in the sidebar background color, headers color and other theme items by changing a single value , `brand-primary` in `resources/config/variables.php`.

for example, 

'brand-primary'          => '#665884',

## Support

Need help or have a question? post a questions at [StackOverflow](https://stackoverflow.com/questions/tagged/stone-theme websemantics)

*Please don't use the issue trackers for support/questions.*

Star this repository if you find this project useful and to show support of the work that has gone into developing this theme.

## Contribution

Contributions to the project is accepted in the form of feedback, bug reports and even better - pull requests :)

## Resources

- [Auto Pyro](https://github.com/websemantics/auto-pyro), PyroCMS deploy tool for faster development experience.
- [Template Template](https://github.com/pyrocms-templates/template-template), Default Pyro Builder template for building Pyro Builder templates.
- [Registry](https://github.com/pyrocms-templates), List of all Pyro Builder available template.
- [Awesome PyroCMS](https://github.com/websemantics/awesome-pyrocms), Curated list of PyroCMS addons and resources.
- [PyroCMS Cheatsheet](http://websemantics.github.io/pyrocms-cheatsheet), List of commands and features for PyroCMS 3.
- [PyroCMS](https://github.com/pyrocms/pyrocms), MVC PHP Content Management System built to be easy to use, theme and develop with. It is used by individuals and organizations of all sizes around the world.

## License

[MIT license](http://opensource.org/licenses/mit-license.php)
Copyright (c) Web Semantics, Inc.