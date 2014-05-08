Clean is a minimal and single user blogging theme that based on [Pure](http://purepelican.com) for [Pelican](http://docs.getpelican.com/) blogs.
=======
## Config
* `COVER_IMG_URL` - Set the sidebar image.
* `PROFILE_IMAGE_URL` - Set the image/logo for the top circle cutout on sidebar.
* `TAGLINE` - Used for the page titles and some meta tags.
* `DISQUS_SITENAME` - Set this to enable disqus comments in articles.
* `GOOGLE_ANALYTICS` - Set the Google Analytics code (eg. "UA-000000-00")
*  `FACEBOOK_APP_ID` - Facebook App ID for Open Graph
* `TWITTER_SITE_ID` - Twitter User Account for Twitter Card
* `SOCIAL` - Set some social links in the sidebar. The format should be like this:
    ```python
    SOCIAL = (
        ('github', 'https://github.com/example/'),
        ('twitter-square', 'https://twitter.com/example'),
    )
    ```
    where the first value of the tuple is the icon name from http://fontawesome.io/icons/ after stripping `fa-` (eg. `fa-github` will be `github`)


## Article Metadata
* `cover_image` - Article's Cover Image for Open Graph and Twitter Card

## Plugins
* [Math Render](https://github.com/getpelican/pelican-plugins/tree/master/render_math) *render_math* plugin for using MathJax to render both MathML and LaTex.
