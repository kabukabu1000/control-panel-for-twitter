# Control Panel for Twitter for Manifest v3

![](icons/icon128.png)

**Control Panel for Twitter is a browser extension which gives you more control over Twitter and adds missing features and UI improvements**


## Releases / What's New?

Manifest v3 provides guidelines for Chrome extension developers as they transition from the legacy extension model to the new model There are some important changes regarding the transition to v3.

If they remain non-compliant with v3, the following consequences are possible

Functionality limitations: extensions that are not v3 compliant may not be able to take advantage of some new features and improvements. This includes changes that are beneficial to extension developers, such as new APIs and security features.

Security issues: Chrome is focused on improving security, and if an older version of an extension is insecure, this could put users' data and privacy at risk. updating to v3 provides a more secure environment.

Loss of compatibility: in future versions of Chrome, extensions that are not compatible with v3 may no longer work. This may result in users not being able to use some of the functionality they need.

Loss of user trust: extensions that do not meet the latest standards in terms of security and functionality may cause users to lose trust in them. It is also important for developers to provide extensions that are secure and useful for users.

In general, support for v3 is important for extension developers. We recommend that you consider moving to v3 to ensure that you can provide safer and more convenient extensions to your users in the wake of future Chrome upgrades and security improvements.

## Features

### Home timeline

- Defaults to the "Following" (chronological) timeline, automatically switching you back if Twitter tries to move you to the "For you" (algorithmic) timeline
- Hide the "For you" timeline tab (default setting)
- Move Retweets to a separate tab (default setting), or hide them entirely
- Move Quote Tweets and replies to them to a separate tab in the Home timeline, or hide them entirely
- Hide Retweets in pinned Lists
- Hide tweets quoting accounts you've blocked or muted
- Mute quoting of specific tweets - adds a "Mute this conversation" menu item to Quote Tweets in the Home and List timelines
- Hide the "Home" heading
- Hide the floating "See new Tweets" button
- Hide "Who to follow", "Follow some Topics" etc. in the Home timeline and elsewhere
- Full-width timeline: hide the sidebar and let timeline content go full-width on Home, Lists and Communities

### UI improvements

- Replace X branding changes
- Hide Views under tweets
- Hide the "Verified" tab on the Notifications page
- Replace Twitter Blue checkmarks with the Blue logo so they're not as easily mistaken for verified accounts, or hide them altogether
- Hide Twitter Blue replies in threads
- Hide Twitter Blue upsells throughout the app
- Hide Subscriptions
- Add "Add muted word" to the "More" menu (desktop) or slide-out menu (mobile)
- Fast blocking - skips the confirm dialog when you try to block an account
- Hide Retweets in user profiles
- Default to "Latest" tab in Search
- When viewing a tweet's Quote Tweets, hide the quoted tweet to make more room for quotes
- Hide "Open app" nags on mobile

### UI tweaks

- Disable use of the Chirp font if you don't like it
- Disable bold and italic text in tweets
- Use the site's normal text font style in the primary navigation menu on desktop to make it less distracting
- Change the navigation menu density on desktop to make it take less room
- Use normal font weight in dropdown menus - if everything's bold, nothing's bold
- Uninvert the Follow and Following buttons to make them less jarring
  - Choice of monochrome or themed (classic) styling for uninverted buttons

### Remove algorithmic content

- Hide "What's happening", "Topics to follow" etc. in the sidebar
- Hide Explore page contents and use it only for searching
- Hide "Discover more" algorithmic tweets when viewing a tweet

### Reduce "engagement"

- Hide metrics
- Reduced interaction mode: hide the action bar under tweets – replies are now the only means of interacting
- Disable the home timeline: find yourself [wasting too much time on Twitter](https://world.hey.com/brecht/free-range-tweet-farming-9399f6e5)? Try preventing use of the home timeline, going to Notifications or Messages by default instead

### Hide UI items you don't use

- Bookmark button under tweets
- Share button under tweets
- Analytics links under your own tweets
- Hide navigation items you don't use on desktop, and other distracting screen elements such as the Messages drawer
- Hide the bottom nav item for Messages on mobile if you don't use it often
- Hide items you don't use in the "More" menu (desktop) or slide-out menu (mobile)




### Language support

日本語 (Japanese)
- Japanese (translation by [@MitoKurato](https://github.com/MitoKurato))

### User script support

 [Control Panel for Twitter is also available as a user script](https://greasyfork.org/en/scripts/387773-control-panel-for-twitter) – to change the default options, you'll need to edit the `config` object at the top of the script.

## Attribution

Icon adapted from "Ibis icon" by [Delapouite](https://delapouite.com/) from [game-icons.net](https://game-icons.net), [CC 3.0 BY](https://creativecommons.org/licenses/by/3.0/)
