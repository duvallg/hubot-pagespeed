### hubot-pagespeed

Hubot will retrieve the Google Insights Pagespeed score and associated stats, displaying them in-channel.

### Usage

```
hubot pagespeed <url> (desktop|mobile) (all|score|stats)
```

### Examples

```
me: hubot pagespeed google.com
```
Retrieves the desktop Pagespeed score for google.com.

```
me: hubot pagespeed google.com desktop all
```
Retrieves all desktop-based Pagespeed information for google.com.

```
me: hubot pagespeed google.com mobile stats
```
Retrieves all mobile-based Pagespeed stats (sans score) for google.com.