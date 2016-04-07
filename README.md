# Stack Templates

Custom templates for [Stack] used by thoughtbot.

[Stack]: http://haskellstack.org

## yesod-heroku

Usage:

    stack new https://raw.githubusercontent.com/thoughtbot/stack-templates/master/yesod-heroku.hsfiles

Initializes a new Yesod project ready to deploy to Heroku.

Differences from yesod-postgres:

* Doesn't contain the example homepage with comments
* Doesn't include Bootstrap CSS and fonts
* Doesn't use OpenID for authentication
* Removes configuration for Keter

## Editing

Three scripts are included to make it easier to edit these templates:

* `bin/split-hsfiles`, which will split an hsfiles template into directories and
  files for easy editing
* `bin/join-hsfiles`, which will merge a directory back into hsfiles format
* `bin/verify-hsfiles`, which will attempt to build a project from the template
  using Stack

## Contributing

We love pull requests from everyone. We expect users to follow our
[code of conduct] while submitting code or comments.

[code of conduct]: https://thoughtbot.com/open-source-code-of-conduct

## License

These templates are Copyright (c) thoughtbot, inc. They are free software, and
may be redistributed under the terms specified in the [LICENSE] file.

[LICENSE]: /LICENSE

## About

These templates are based on the [official templates].
mainained by [thoughtbot].

![thoughtbot](https://thoughtbot.com/logo.png)

The names and logos for thoughtbot are trademarks of thoughtbot, inc.

We love open source software!
See [our other projects][community]
or [hire us][hire] to help build your product.

[thoughtbot]: https://thoughtbot.com
[official templates]: https://github.com/commercialhaskell/stack-templates
[community]: https://thoughtbot.com/community?utm_source=github
[hire]: https://thoughtbot.com/hire-us?utm_source=github
