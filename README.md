# BetterFox
about:config tweaks to enhance [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/ "Firefox Homepage"). Files are updated as needed for your [user.js](http://kb.mozillazine.org/User.js_file).


## Simple goals:
1) **Minimalism:** get what isn't needed out of the way
2) **Efficiency:** unleash Firefox's ability to be fast and performant
3) **Security:** sensible privacy and security without causing site breakage


## Simple configs:
   
| List      | Description |
|:---------:|-------------|
| [Fastfox](https://github.com/yokoffing/Better-Fox/blob/master/FastFox.js)   | Immensely increase Firefox's browsing speed. Give Chrome a run for its money!|
| [SecureFox](https://github.com/yokoffing/Better-Fox/blob/master/SecureFox.js) | Remove Telemetry, Mozilla experiments, Google Safe Browsing, and search engine suggestions in URL bar. Auto-upgrade mixed content to HTTPS. Various privacy enhancements. |
| [PeskyFox](https://github.com/yokoffing/Better-Fox/blob/master/PeskyFox.js)  | Unclutter the new tab page. Remove Pocket and form autofill. Prevent Firefox from serving annoying webpage notifications. |
| [SmoothFox](https://github.com/yokoffing/Better-Fox/blob/master/SmoothFox.js) | Get Microsoft Edge-like smooth scrolling on your favorite browser. |
| [user.js](https://github.com/yokoffing/Better-Fox/blob/master/user.js) | All the essentails. None of the breakage. Users may download this list as their own user.js. |

## Who is this setup for?
**If you want a secure, blazing fast browsing experience, and don't want to deal with breakage, this setup is for you.** My objective is to make the defaults sufficient enough for the average privacy-minded user, but remain trouble-free enough that my grandmother could use it. <strike>(That puts a whole new twist on being a foxy grandma!)</strike> Edit: Sorry for the dad joke 😓

## about:Privacy
My guiding principle was: "If it breaks it, it doesn't make it!" So things like WebGL and DRM are still enabled, and you won't find settings like `privacy.resistFingerprinting` or `network.http.referer.XOriginPolicy` mentioned here. BetterFox is designed to set-and-forget, not to troubleshoot and tinker. You can compare different user.js files [here](https://yokoffing.github.io/compare-user.js/).

Betterfox was created with a [less is more](https://medium.com/the-mission/less-is-more-the-minimum-effective-dose-e6d56625931e) mentality. Most repos I've encountered have niche privacy and security concerns with little regard for speed, annoyances, or mainstream use. The average user doesn't need all `user_prefs` altered to get the results they want.

## Assumptions
That being said, Betterfox does make some assumptions: **Google Safe Browsing is completely disabled.** If you don't have other means of protection, you should remove the preferences listed and leave it turned on. **Saving passwords natively** is also disabled. Betterfox assumes you use a password manager. If you don't have something like [LastPass](https://addons.mozilla.org/en-US/firefox/addon/lastpass-password-manager/) or [Bitwarden](https://addons.mozilla.org/en-US/firefox/addon/bitwarden-password-manager/), then remove the prefs that disable this functionality. etc, etc.

You should have [Ghostery](https://github.com/yokoffing/Better-Fox/wiki/Ghostery) or [uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/) for ad and tracker blocking. Using DNS-level protection like [NextDNS](https://nextdns.io/?from=xujj63g5) is highly recommended.

If your threat level calls for anonymity and not just reasonable privacy, please use the [TOR browser](https://www.torproject.org). 👍


## [Wiki](https://github.com/yokoffing/Better-Fox/wiki)
Check out our [most recommended extension](https://github.com/yokoffing/Better-Fox/wiki/Ghostery)!


## Credit
Where there is similiarity to other authors, credit goes to them.

<a href="https://www.buymeacoffee.com/yokoffing" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>
