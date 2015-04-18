### hubot-pagespeed

Hubot will retrieve the Google Insights Pagespeed score and associated stats, displaying them in-channel.

### Usage

```
hubot pagespeed <url> (desktop|mobile) (all|score|stats)
```

### Examples


Retrieve the desktop Pagespeed score for google.com.
```
me: hubot pagespeed google.com
```

Retrieve all desktop-based Pagespeed information for google.com.
```
me: hubot pagespeed google.com desktop all
```

Retrieve all mobile-based Pagespeed stats (sans score) for google.com.
```
me: hubot pagespeed google.com mobile stats
```