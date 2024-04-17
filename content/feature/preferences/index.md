+++
title = 'Preferences'
summary = 'Customize your accounts and Feditext as a whole.'
+++

## Account preferences

Preferences in this section apply to your currently selected Fediverse account, and its name is displayed at the top of the section.

### Filters

Review and edit your [filters](../filter/#filters).

Not all instances support filters. If your instance doesn't support them, this preference won't be shown here.

### Push notifications

Control which types of push notification you receive from this account, and who you receive them from: everyone, users you follow, users that follow you, or no one.

Not all instances support push notifications. If your instance doesn't support them, this preference won't be shown here.

### Muted Users

Review and edit your list of [muted users](../filter/#mutes).

Not all instances support muting. If your instance doesn't support them, this preference won't be shown here.

### Blocked Users

Review and edit your list of [blocked users](../filter/#blocks).

### Blocked Domains

Review and edit your list of [blocked domains](../filter/#domain-blocks).

Not all instances support blocking domains. If your instance doesn't support them, this preference won't be shown here.

### Use preferences from server

Some account preferences can be read from your instance and shared across all clients, including but not limited to Feditext. When this is enabled, those preferences are dimmed and cannot be changed.

### Posting defaults

#### Default visibility

Posts you create will default to this visibility level. You can change it before posting.

This preference can be read from your instance.

#### Mark content sensitive by default

Posts you create will default to being marked as sensitive.

This preference can be read from your instance.

#### Default language

Posts you create will default to this language. You can change it before posting.

This preference can be read from your instance.

### Viewing defaults

#### Expand media

Controls default media visibility when new posts are received. You can choose to show all media, hide sensitive media, or hide all media. Tap media to show it.

This preference can be read from your instance.

#### Always expand content warnings

Expand all posts with content warnings when they're received. Useful if you're in a community that uses them as topics rather than warnings.

This preference can be read from your instance.

### Accent color

Use accent colors to visually keep track of which account you're using. This is handy if you have multiple accounts with similar profile pictures, or just want to make Feditext use your favorite color.


## App preferences

Preferences in this section apply to the whole app.

### App Icon

Customize the way Feditext appears on your Home Screen and in your App Library by picking from one of our app icons. You'll get an OS alert box confirming that you've changed the icon.

### Appearance

Keep Feditext's UI in light mode or dark mode regardless of your system settings.

### Notifications

#### Include pictures

*TODO*

#### Include account name

*TODO*

#### Group

When a post is faved or boosted by multiple people, or multiple people follow you, this condenses what would otherwise be multiple notifications into a single summary notification, making your notifications easier to read.

This preference currently applies only to Feditext's Notifications tab, not to OS notifications.

#### Sounds

You can choose which types of notification will play sounds when they're received.


### Status word

Prefer "toot" to "post"? Return to the pre-Mastodon-4.0 era. (The API calls them "statuses" anyway. Don't tell anyone.)

### Keyboard

The default on-screen keyboard layout includes the `@` and `#` keys, but you can replace them with the return key.

### Posting languages

Select the languages that will appear in the language menu when you post, and the order they'll appear in.

Note that some instances may not support all posting languages, and will silently ignore those languages in favor of a default. If you use a less common language, please check with your instance administrator.

### Send description metadata as alt text on media you upload

Use description metadata (aka photo comments) to automatically fill in alt text.

Turn this off if you use photo comments for some purpose other than descriptive text.


### Interaction features

Features related to boosts and favs.

#### Show boost and favorite counts

Control whether you see these numbers when looking at posts in a timeline. Turn this off for a more relaxed numbers-light reading experience.

#### Require double tap to reblog

Require a second tap to confirm a boost.

#### Require double tap to favorite

Require a second tap to confirm a fav.


### External link preferences

#### Open links in default browser

Turn this on to open external links in your default browser (often but not always Safari). Turn this off to open links in a Safari browser view inside Feditext.

#### Open links in other apps when available

Visible only when you've opted to open external links in Feditext. Turn this on to attempt to open external links related to specific apps in that app, if the app is installed. For example, this would open YouTube links in the YouTube app instead of in Feditext's browser.


### Animation preferences

#### Autoplay GIFs

Choose to autoplay animated GIFs everywhere, only if you're on Wi-Fi, or never.

#### Autoplay videos

Choose to autoplay videos everywhere, only if you're on Wi-Fi, or never.

#### Animate avatars

Choose to play avatar animations everywhere, in profiles only (but not on timelines), or never.

#### Animate custom emoji

Choose to play custom emoji animations or not.

#### Animate profile headers

Choose to play profile header animations or not.


### Reading preferences

#### Hide "Show Less" content warning button

Hide the "Show More" button's counterpart after you've expanded a post with a content warning. Doesn't apply to long posts, which will always show the "Show Less" button.

#### Fold long text

Visually collapse very long posts, in the same way that posts with content warnings are collapsed. Useful if you're in a part of the Fedi where post length restrictions are uncommon.

#### Visually de-emphasize trailing hashtags

It's common Fedi practice to add hashtags to posts to make discovering them easier, but that practice adds visual noise. This preference shrinks and dims hashtags at the end of a post, so that the post's text stands out.

<div id="hashtag-de-emphasis-examples">
<style>
  #hashtag-de-emphasis-examples {  
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(500px, 1fr));
  }
</style>

{{< figure
class="hashtag-de-emphasis-on"
src="hashtag-de-emphasis-on.png"
alt="Post with eight hashtags, dimmed and smaller than the post's actual text"
caption="Hashtag de-emphasis on"
width=500
height=235
loading=lazy >}}

{{< figure
class="hashtag-de-emphasis-off"
src="hashtag-de-emphasis-off.png"
alt="Post with eight hashtags, bright like other links and the same size as the post's actual text"
caption="Hashtag de-emphasis off"
width=500
height=250
loading=lazy >}}

</div>

#### Colorize visibility icons

Feditext always distinguishes post visibility with icon shapes. This preference adds color to make it even easier to distinguish public posts from private posts.

<div id="colorized-visibility-icons-examples">
<style>
  #colorized-visibility-icons-examples {  
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(257.5px, 1fr));
  }
</style>

{{< figure
src="colorized-visibility-icons-on.png"
alt="Solid, brightly colored post visibility icons"
caption="Colorized visibility icons on"
width=257.5
height=60
loading=lazy >}}

{{< figure
src="colorized-visibility-icons-off.png"
alt="Outlined gray post visibility icons"
caption="Colorized visibility icons off"
width=257.5
height=60
loading=lazy >}}

</div>

#### Home timeline position on startup

Remember where you were the last time you were using Feditext, or always start reading from the newest posts.


### Advanced

Most people won't need this section. Preference controls in this section may be changed or removed at any time.

#### API compatibility mode

Controls which instance features are displayed in Feditext's interface. Intended for users with accounts on experimental or modified Fediverse instances. Most users should use "Off".

"Enable all API calls, attempt error recovery" will enable all features regardless of whether they're known to work with your instance. You can use this if your instance has a feature that Feditext supports, but it's not showing up in Feditext. If a feature doesn't work, it will substitute stub data where possible: for example, if your instance doesn't support mutes, Feditext will show the muted users list, but it will be empty.

"Enable all API calls, fail on errors" will enable all features regardless of whether they're known to work with your instance. If a feature doesn't work, it will fail, usually resulting in an error message. This option is meant for instance software developers testing against Feditext.

This setting does not take effect until you tap "Apply new compability mode".

#### Clear navigation cache

When you tap a link, Feditext may use your instance to check if it's a Fediverse post, a Fediverse account, or a regular web page. The navigation cache stores the results. If links don't navigate to what you expect to see there, you can try clearing the navigation cache; however, this should be very rare. Restarting the app will have the same effect.

#### Use toasts to display transient errors

Feditext normally uses "toast"-style pop-up messages to announce transient or non-actionable errors, for example, trying to load more posts when you don't have a network connection, or trying to load a post that no longer exists. Feditext's toasts should be suitable for both sighted and VoiceOver users; however, if you notice any issues with your assistive tech and toasts, or prefer modal error dialogs, you can turn toasts off here.
