# LibrePDX Community Website

This site is written using [Jekyll](http://jekyllrb.com/) and is compatible
with [GitHub Pages](http://pages.github.com/).


## Contributing
This is a community maintained site! Everyone is welcome to submit new
content and contribute back in any way they can think of. We try to
make the process as easy as possible for all technical skill levels.
If you...

* **understand what git, jekyll and github pull requests are**, we encourage
  you to fork this repository, make changes and then submit a pull request.
  See the [Installation](#installation) section below. If you are writing a
  blog post that you would like other people to help contribute to, please
  consider using the wiki instead of a fork.

* **have experience editing wikis**, we encourage you to use the GitHub
  [wiki](https://github.com/LibrePDX/librepdx.org/wiki) to write new content
  such as _open source success stories_. When you are done or are ready to
  solicit feedback from the community, create a new issue in the
  [issue tracker](https://github.com/LibrePDX/librepdx.org/issues) and
  include a link to the wiki page. People can then provide feedback and
  hopefully incorporate it back into the site when you are ready.

* **want to submit an idea, bug or small change**, we encourage you to go
  ahead and create a new issue in the
  [issue tracker](https://github.com/LibrePDX/librepdx.org/issues).

* **are not sure how to submit issues, use a wiki or have a GitHub account**,
  we encourage you to write down your ideas and any other notes in our
  [public notepad](https://notes.typo3.org/p/LibrePDX_Website). No username
  or password is required, just write! The community will keep an eye on things
  people write there and try to incorporate those ideas back into the site.

* **want to share your passion and learn about other people**, we encourage you
  to attend one of our [regular events](http://calagator.org/events/search?tag=librepdx)
  or learn about the [many](http://calagator.org/events)
  [other](http://portland.activatehub.org/) [things](http://epdx.org/resources)
  happening around Portland. Spread the word and discover what awesome things
  other people in the community may be doing; we would love to hear about it!


## License
Contributors retain copyright of their works and agree to release it for use
under the [CC-BY-SA 3.0 license](http://creativecommons.org/licenses/by-sa/3.0/us/).

For more information, see the [LICENSE](LICENSE) file.


## Installation
These instructions only apply if you plan to work on a forked copy of this
repository and eventually submit a pull request.

Assumptions:

* You are using [rbenv](https://github.com/sstephenson/rbenv),
  [rvm](https://rvm.io/) or generally know how to use
  [Bundler](http://bundler.io/).
* You have a copy of ruby 1.9.3 installed (`ruby -v`).
* You've forked the repository and have it checked out locally.
* You have a console open and are in the project's top-level directory.

To install any dependencies:
```plain
bundle install
```

To run a copy of Jekyll locally:

```plain
bundle exec jekyll serve -wH localhost
```

You should now be able to access the site at [http://localhost:4000](http://localhost:4000).
Any changes you make should be visible upon refreshing the page.

Documentation on how to use Jekyll and the Liquid templating system:

* http://jekyllrb.com/docs/home/
* http://wiki.shopify.com/Liquid
