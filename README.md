# Security Notes - Dummy Guide

This document goes over the global lines of protecting you, your accounts and your data. Not all steps are required, but are recommended. Keep in mind that these changes will be different than your normal Chrome/Google configuration, and is selected to work as closely to that as possible.

## Passwords and accounts

One of the most important things to do is to ensure that all accounts are safe. This can simply be done by making your passwords very difficult to crack. But then you must remember all of them. That's what a password manager if for. It automatically fills everything in for you. 2 factor authentication is also an important step towards safety.

### Password Manager: [Bitwarden](https://bitwarden.com/)

![bitwarden](./assets/icons/128x128/bitwarden.png)

There are many options for password managers. And also with many different prizes. Some are also free. One of them is Bitwarden. This password manager is open-source and has a free plan. If you run the code yourself you even get the premium features for free, but they are not really necessary for a normal user.

Because the data is encrypted on your own device, even Bitwarden doesn't know the passwords. **So never lose your password, because the support team can not get it back, nor your passwords stored.**

![bitwarden](./assets/bitwarden/bitwarden.png)

### 2FA - 2 Factor Authentication: [Authy](https://authy.com/)

![authy](./assets/icons/128x128/authy.png)

2FA is a technology that takes security to the next level. When you normally log in with only a password, you must now also fill in a number code. This code changes every 30 seconds. As a result, your account is safer and less likely to be hacked.

Authy is a program where you can save these codes. If a service or website supports 2FA, you will be asked for an authentication app. Usually Google authenticator is recommended, but Authy is not from Google, and therefore has my preference.

If you use 2FA, always take your phone with you. **You can't get into your account without 2FA if it's turned on. The only way is with backup codes. Do not lose those.** 2FA can be turned off again.

*2FA can also be in the app of Bitwarden, but still needs an authentication app for the 2FA of the program itself. It is also a paid feature and not included in the free plan.*

![authy](./assets/authy/authy.png)

### Monitors on data breach: [Firefox Monitor](https://monitor.firefox.com/)

![firefox-monitor](./assets/icons/128x128/firefox-monitor.png)

There are regularly services that are hacked and where the data is sold on the black market. With a monitor service you can keep an eye on whether your data has been taken with a data breach or hack. With FireFox Monitor you can enter emails that need to be scanned for data breaches. The service will keep you up to date if something happens to your data and will send an email.

![firefox-monitor](./assets/firefox-monitor/monitor.png)

## Browser

It is very important to use the correct browser and search engine. that way, your data is safer.

### 1st browser of choice: [Firefox](https://www.mozilla.org/en-us/firefox/new/)

![firefox](./assets/icons/128x128/firefox.png)

Firefox is one of Chrome's largest opponents. But where Chrome is from Google, Firefox is made by Mozilla. This is a non-profit organization with the user on the number one spot. They have built Firefox from the ground up. So it is possible that things don't work nicely. But that happens the other way around, because most websites are made using Firefox for testing.

#### Firefox Settings

There are things that need to be adjusted.
First is the default search engine. As explained in [this](#search-engine) section, Google isn't the best search engine to use. First, set that to DuckDuckGo in the dropdown menu. Along with that, turn off search suggestions. This is a personal preference, but will make the amount of data send to the server less. These settings can be changed here:

```txt
about:preferences#search
```

![default-search-engine-image](./assets/firefox/default-search-engine.png)

![search-suggestions](./assets/firefox/search-suggestions.png)

Then, you also want to make the tracking protection stronger. You also want to always send websites the `Do Not Track` attribute. That way, less data is collected through websites. Next, if you're going to use a password manager, as explained [here](#password-manager-bitwarden), turn off password autofill. You can also disable suggestions from history a bit lower down. You also want to block popups and warn be warned when extensions are installed. Last, disable telemetry. These settings can be changed here:

```txt
about:preferences#privacy
```

![enhanced-tracking-protection](./assets/firefox/enhanced-tracking-protection.png)

![do-not-track](./assets/firefox/do-not-track.png)

![no-password](./assets/firefox/no-password.png)

![history-suggestions](./assets/firefox/history-suggestions.png)

![block](./assets/firefox/block.png)

![telemetry](./assets/firefox/telemetry.png)

Last, you can either enable Firefox to delete all browsing data and cookies, or only delete the history. The first logs you out of all your sessions each time the browser closes. The later, my preferred choice in combination with some cookie container [extensions](#firefox-extensions), is enabled the following.

![history](./assets/firefox/history.png)

#### Firefox extensions

These extensions are my recommend extensions that i use with Firefox. They block requests that can track you around the web. Keep in mind that the cookie extensions can break websites when they're enabled.

`General`

- [Link](https://addons.mozilla.org/en-us/firefox/addon/duckduckgo-for-firefox/) - DuckDuckGo Privacy Essentials
- [Link](https://addons.mozilla.org/en-us/firefox/addon/ublock-origin) - uBlock Origin
- [Link](https://addons.mozilla.org/en-us/firefox/addon/privacy-badger17/) - Privacy Badger
- [Link](https://addons.mozilla.org/en-US/firefox/addon/decentraleyes) - Decentraleyes
- [Link](https://addons.mozilla.org/en-us/firefox/addon/https-everywhere) - HTTPS Everywhere
- [Link](https://addons.mozilla.org/en-US/firefox/addon/i-dont-care-about-cookies) - I don't care about cookies
- [Link](https://addons.mozilla.org/en-US/firefox/addon/cookie-quick-manager) - Cookie Quick Manager
- [Link](https://addons.mozilla.org/en-us/firefox/addon/bitwarden-password-manager/) - Bitwarden

`Cookie`

- [Link](https://addons.mozilla.org/en-US/firefox/addon/facebook-container) - Facebook Container
- [Link](https://addons.mozilla.org/en-us/firefox/addon/google-container/) - Google Container
- [Link](https://addons.mozilla.org/en-us/firefox/addon/microsoft-container) - Microsoft Container

### 2nd browser of choice: [Brave](https://brave.com/)

![brave](./assets/icons/128x128/brave.png)

Brave is another good alternative. Where Firefox was built off the ground, Brave is built on the open-source chromium. That is the base of Chrome and many other browsers. But Brave removed anything to do with Google. As a result, it works the same as Chrome, but it's way better behind the scenes.

#### Brave settings

Almost all Brave's settings are good out of the box. The only thing that is not good is their own crypto currency. You can earn this by viewing ads. However, this is not realistic with how little money you get. There are some settings that need to be changed to completely disable this:

```txt
TODO: This section will be filled in later
```

#### Brave extensions

`General`

- [Link](https://chrome.google.com/webstore/detail/duckduckgo-privacy-essent/bkdgflCldnnApblkhphbgPGGdiikPpg) - DuckDuckGo Privacy Essentials
- [Link](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpaMameJdnhcphJbkeiaGm) - uBlock Origin
- [Link](https://chrome.google.com/webstore/detail/privacy-badger/pkehgijcmpdhfbdbbnkijodmdjhbjlgp) - Privacy Badger
- [Link](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp) - HTTPS Everyhere
- [Link](https://chrome.google.com/webstore/detail/bitwarden-free-password-m/nngceckbapebfimnlniiahkandclbb) - Bitwarden

## Search engine

Google as a search engine has its advantages. The user interface is nice to work with and there are many nice to have things, like movie information and Wikipedia summaries that are displayed directly. But the search results are all adapted to you, through tracking. Every letter that you type goes to Google. And in some cases the search results are also filtered to what the government wants it to be.

### The better alternative: [DuckDuckGo](https://duckduckgo.com/about)

![duckduckgo](./assets/icons/128x128/duckduckgo.png)

DuckDuckGo is an alternative search engine that doesn't track you. The results are also not filtered. You will also have the standard things, such as suggestions during typing and information that is displayed directly, such as Wikipedia.

You also have "[Bangs](https://duckduckgo.com/bang)". These are short sets from characters that you put in front of your search. If you want to find something on Wikipedia directly, then type `!w DuckDuckGo` to search for DuckDuckGo on Wikipedia.

## IDFA (identifier for advertisers)

On phones there is something like an IDFA. Almost all apps use that to send your data to a server. With that number that data is linked to you. You can reset this how often you want. You also have to turn the personalization of ads. This can be done like this:

```txt
TODO: This section will be filled in later
```

```txt
This section will be expanded as soon as this can be turned off.
```

## Windows settings

Not only the browser must be protected. The Windows installation itself must also. the next few chapters will go over some things you can do to make your Windows instalation cleaner, more private and more secure.

### The normal settings menu

Windows automatically sends data from your computer to Microsoft. These settings are on, but can also be turned off. Also, Windows uses your bandwidth to install updates on other Windows computers. As a result, your internet is slow. You can also disable this.

### Bloatware

As you install Windows fresh or you buy a new computer with Windows, both ways you end up with a lot of apps that you will never use. For some people that is the Feedback Hub, for others the Xbox Game Bar. Some People also dislike Microsoft Edge, which will always open when searching with the Windows Search Bar. Others might want to completely remove OneDrive as well.

#### A simple tool: [PyDebloatX](https://pydebloatx.com/)

![pydebloatx](./assets/icons/128x128/pydebloatx.png)

PyDebloatX is a small tool which allows you to uninstall most of the default apps that Windows comes with. Just check the items you want to remove, and click `Uninstall`. The program will do the rest fro you. If you decide that you want to reinstall an app, just click the button of the Windows Store on the side, and you'll be redirected to the Microsoft Store page of that app.

![pydebloatx-in-action](./assets/pydebloatx/pydebloatx-in-action.png)

#### Going to the next level: [Windows10Debloater](https://github.com/sycnex/windows10debloater)

Windows10Debloater is a more advanced tool to remove other programs and services that lie deeper into Windows. **That makes this tool more dangerous to use, but isn't too risky.** With this, you can completely remove OneDrive, telemetry and other things like registry keys that are not used anymore. The interface may freeze, but in the terminal it's continuing to work. Just wait till it's back.

My recommened options are to disable Cortana and edge PDF, then disable telemetry, uninstall OneDrive and lastm remove the bloatware regkeys.

![windows10debloater-in-action](./assets/windows10debloater/windows10debloater-in-action.png)

#### The final step: [EdgeDeflector](https://github.com/da2x/edgedeflector)

EdgeDeflector is a tool that intercepts Edge links, and modifies them to be opened in the default browser. That way, Edge will never open again. In combination with the Firefox extension [Bing to DuckDuckGo](https://addons.mozilla.org/en-us/firefox/addon/bingtoduckduckgo) you can make sure all searches go through DuckDuckGo, which is better to use as explained [here](#search-engine). DuckDuckGo "Bangs" also work here too!
