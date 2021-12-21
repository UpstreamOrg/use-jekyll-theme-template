# For from [Type-on-Strap](https://github.com/sylhare/Type-on-Strap)

## Usage

### As a github page 📋

1. Fork and clone the [Type on Strap repo](https://github.com/sylhare/Type-On-Strap): `git clone https://github.com/Sylhare/Type-on-Strap.git`
2. Install [Jekyll](https://jekyllrb.com/docs/installation/): `gem install jekyll`, check [#1](https://github.com/Sylhare/Type-on-Strap/issues/1) if you have a problem.
3. Install the theme's dependencies: `bundle install`
4. Customize the theme
	- GitHub Page: [update `_config.yml`](#site-configuration)
5. Run the Jekyll server: `bundle exec jekyll serve`

### Use as Ruby Gem 💎

You can use Type-on-strap as a [gem](https://rubygems.org/gems/type-on-strap). 

Ruby Gem Method
Add this line to your Jekyll site's Gemfile (or create one):

```ruby
gem "type-on-strap"
```

Add this line to your Jekyll site's `_config.yml` file:

```yml
theme: type-on-strap
```

Then run Bundler to install the theme gem and dependencies:

```bash
bundle install
```

Then you can start adding content like:
  - Add a `index.html` file
  - Add the feature page you want. (ex: as it is already in `pages`)
  - Add posts in `_posts` and `_portfolio` to be displayed

### Remote Theme

Now you can use any theme gem with GitHub pages with [29/11/2017 Github Pages Broadcast](https://github.com/blog/2464-use-any-theme-with-github-pages).
For that remove all `theme:` attributes from `_config.yml` and add instead:

```yml
remote_theme: sylhare/Type-on-Strap 
```
