# Trackula Theme for Hugo

This theme is created from scratch for use in the Trackula project.

## Installation

Copy the theme onto your themes directory. Then, use the official
[setup guide](https://gohugo.io/overview/installing/) of Hugo.

## Configuration

After installing, take a look at the required configuration options.

For the moment, this section is lacking documentation, please find
variable usages and report their documentation here.


### Gravatar

This theme supports gravatar-based user posts. In order to use it,
add an "email" property with your email to your user account and
configure your avatar at [Gravatar](https://gravatar.com/) with
the same email address.


### Need more style customizations?

Create `css/custom.css` in your `<<base dir>>/static` folder and add your custom styling.

### Comments

Comments are not implemented at this moment.

### Matomo

You can optionally enable Matomo for user analytics. Type your tracking code in the configuration.toml.

```toml
piwikId = "1"
piwikJs = "https://example.com/piwik/piwik.js"
```

Leave the `googleAnalytics` key empty to disable it.

### Make the contact form working

Since this page will be static, you can use [formspree.io](//formspree.io/) as proxy to send the actual email. Each month, visitors can send you up to one thousand emails without incurring extra charges. Begin the setup by following the steps below:

1. Enter your email address under 'email' in the [`config.toml`](https://github.com/appernetic/hugo-nederburg-them/tree/master/exampleSite/config.toml)
2. Upload the generated site to your server
3. Send a dummy email yourself to confirm your account
4. Click the confirm link in the email from [formspree.io](//formspree.io/)
5. You're done. Happy mailing!

### Nearly finished

In order to see your site in action, run Hugo's built-in local server.

```
$ hugo server
```

Now enter [`localhost:1313`](http://localhost:1313) in the address bar of your browser.


## Things to do and not (yet) implemented

 - Add the possibility for a description for each category.
 - ~~Add pagination to the front page.~~
 - Add dropdown menu option to the left sub menu.
 - Add previous next pagination in blog post.
 - Add a search function.
 - Do a SEO check of site structure and code
 - Page speed check
 - ~~Add a default favicon~~
 - Check that Disqus don’t break anything.

## Contributing

Have you found a bug or got an idea for a new feature? Feel free to use the [issue tracker](https://github.com/appernetic/hugo-nederburg-theme/issues) to let me know. Or make directly a [pull request](https://github.com/appernetic/hugo-nederburg-theme/pulls).

## License

This port is released under the MIT License.


## Thanks

Thanks to [Steve Francia](https://github.com/spf13) for creating Hugo and the awesome community around the project. And also thanks to [competethemes](https://www.competethemes.com/tracks/) for creating this awesome theme.

## Sponsors

List of all the great people and organisations that help us fund this open source work.

If you want to help support check out my Patreon @ https://www.patreon.com/appernetic

[Timothy D. Swieter](https://github.com/Swieter) 
