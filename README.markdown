## What is liquidhaskell-blog?

A fork and minor modification of Octopress, used to generate blog articles
illustrating [liquidhaskell](https://github.com/ucsd-progsys/liquidhaskell)

## Installation and Use

1. Follow the basic Octopress docs for basic setup.

2. Update the Rakefile variables `lhs_dir`, `ssh_user`, `document_root`
   Make sure you have the right URLs in `_config.yml`, `config.rb` and `Rakefile`
   [See this](http://octopress.org/docs/deploying/subdir/)

3. Populate the  `source/_posts` directory with the usual .markdown files. 
   Make sure they don't have the suffix `.lhs.markdown` as those are deleted 
   at each invocation of `generate_liquid`.

4. Run `rake generate_liquid`

5. Deploy with `rake rsync`

The subdirectory path thing is a mess, see [this](http://octopress.org/docs/deploying/subdir/) for details

## What is Octopress?

Octopress is [Jekyll](https://github.com/mojombo/jekyll) blogging at its finest.

1. **Octopress sports a clean responsive theme** written in semantic HTML5, focused on readability and friendliness toward mobile devices.
2. **Code blogging is easy and beautiful.** Embed code (with [Solarized](http://ethanschoonover.com/solarized) styling) in your posts from gists, jsFiddle or from your filesystem.
3. **Third party integration is simple** with built-in support for Twitter, Pinboard, Delicious, GitHub Repositories, Disqus Comments and Google Analytics.
4. **It's easy to use.** A collection of rake tasks simplifies development and makes deploying a cinch.
5. **Ships with great plug-ins** some original and others from the Jekyll community &mdash; tested and improved.

## Documentation

Check out [Octopress.org](http://octopress.org/docs) for guides and documentation.


## Contributing

We love to see people contributing to Octopress, whether it's a bug report, feature suggestion or a pull request. At the moment, we try to keep the core slick and lean, focusing on basic blogging needs, so some of your suggestions might not find their way into Octopress. For those ideas, we started a [list of 3rd party plug-ins](https://github.com/imathis/octopress/wiki/3rd-party-plugins), where you can link your own Octopress plug-in repositories. For the future, we're thinking about ways to easier add them them into our main releases.


## License
(The MIT License)

Copyright © 2009-2011 Brandon Mathis

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the ‘Software’), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED ‘AS IS’, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


#### If you want to be awesome.
- Proudly display the 'Powered by Octopress' credit in the footer.
- Add your site to the Wiki so we can watch the community grow.
