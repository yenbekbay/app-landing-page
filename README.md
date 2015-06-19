## How to use

1. Start by [installing Bundler](http://bundler.io) `sudo gem install bundler`
2. [Fork the landing page repository](https://github.com/yenbekbay/app-landing-page/fork)
3. Clone the repository you just forked: `git clone https://github.com/YOUR-USER/app-landing-page`
4. Enter `cd app-landing-page`
5. Then run `bundle install` to get [Jekyll](http://jekyllrb.com) and all the dependencies.
6. Edit `_config.yml` and `content.html` as needed.
7. Run the Jekyll server with `bundle exec jekyll serve`
8. Go to `http://localhost:4000/app-landing-page/`

Note:
If you edit css files, your landing page will update, but if you edit html files, the changes won't be reflected until you run `bundle exec jekyll serve` again.

## Deploy your site to GitHub Pages

Deploy your site to GitHub Pages with `git push -f origin master:gh-pages`

If you are planning on using a custom domain to direct to your site, modify the CNAME file as described [here](https://help.github.com/articles/adding-a-cname-file-to-your-repository/).

Check the [GitHub Pages Basics](https://help.github.com/categories/github-pages-basics/) for more information.
