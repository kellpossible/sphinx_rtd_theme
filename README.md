# Zola Read the Docs Theme

The `zola_rtd_theme` is a sphinx_ theme designed to look modern and be
mobile-friendly. This theme is primary focused to be used on readthedocs.org_
but can work with your own sphinx projects. To read more and see a working demo
head over to **TODO**


## Installing



## Configuration

The `zola_rtd_theme` is highly customizable on both the page level and on a
global level. To see all the possible configuration options read the configuring
docs **TODO**


## Contributing

If you would like to help improve the theme or have more control over the theme
in case of a fork please read our contributing guide **TODO**

## Development Plan

I can make use of
https://www.getgutenberg.io/documentation/templates/pages-sections/#table-of-contents
in a similar manner to
https://github.com/Keats/tera/blob/master/docs/templates/docs.html, and for
items which don't fall within the current document's tree, we can ignore them
and not render them, similar to the original Sphinx theme, which only shows
siblings of the current level, and parent's siblings. It does not show sibling
children.