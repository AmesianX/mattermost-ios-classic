# Mattermost iOS Application Changelog

## Release v3.5.0  

Released 2016-11-16

### Improvements
- Added support for playing video (MP4) and audio files from the webview.

### Bug Fixes
- Fixed an issue where users had no way to get back to the app when the "Download" link is clicked on images or PDF files.

### Contributors

Many thanks to all our contributors. In alphabetical order:

- [coreyhulen](https://github.com/coreyhulen)
- [thomochop](https://github.com/thomchop)

## Release v3.4.0  

Released 2016-09-16

### Bug Fixes
- Fixed issue where channels were reloading each time the app was opened.

### Contributors

Many thanks to all our contributors. In alphabetical order:

- [coreyhulen](https://github.com/coreyhulen)

## Release v3.3.0  

Released 2016-08-16

### Improvements
- Keyboard now closes when a user executes a search.
- Enter key now creates a new line instead of sending the message.
- Made it easier for users to discover the mobile app by adding a download page that appears when the site is accessed on a mobile web browser. Also added download links to the welcome email, tutorial, and main menu.
- Permalinks are now available on mobile.
- Clicking on the ... menu when in the right-hand sidebar view is now easier.
- Auto-complete enabled for "from:" and "in:".

### Bug Fixes
- Fixed issue where center channel appears blank after initial page load.

### Contributors

Many thanks to all our contributors. In alphabetical order:

- [coreyhulen](https://github.com/coreyhulen)
- [hmhealey](https://github.com/hmhealey)
- [jasonblais](https://github.com/jasonblais)

## Release v3.2.0  

Released 2016-07-16

### Bug Fixes
- When a session ends or is revoked, push notifications should now start sending again when the user logs back in
- "Refresh/Logout" prompt no longer appears frequently when opening the app

### Contributors

Many thanks to all our contributors. In alphabetical order:

- [coreyhulen](https://github.com/coreyhulen)

## Release v3.1.0  

Released 2016-06-16

### Features 
- Added support for sending notifications to Apple Watch 
- **Account Settings** > **Notifications** > **Mobile push notifications** option lets users to enable mobile push notifications for all activity, mentions only, or to disable push notifications. 
- Push notifications sent even if a user is online on desktop.
- Removed auto-capitalization on login screen, so email is no longer capitalized.

### Contributors

Many thanks to all our contributors. In alphabetical order:

- [coreyhulen](https://github.com/coreyhulen)
- [lfbrock](https://github.com/lfbrock)

## Release v3.0.0  

Released 2016-05-16

### Features   
- Added support for multiple teams on the same server
- Added auto-correct
- New option to include message snippets in push notifications

### Breaking Change  
- Users of Mattermost 3.0 server need to install new iOS 3.0 app. iOS 2.x apps are not compatible with Mattermost 3.0 server, and iOS 3.0 app is not compatible with Mattermost 2.x server. [See Mattermost v3.0 changelog for further details](http://docs.mattermost.com/administration/changelog.html#release-v3-0-3)

### Contributors

Many thanks to all our contributors. In alphabetical order:

- [coreyhulen](https://github.com/coreyhulen)
- [it33](https://github.com/it33)


## Release v2.0.0  

### Features   
- Added support for GitLab single-sign-on 
- Added support for Active Directory and LDAP single-sign-on (available with pre-released Mattermost Enterprise Edition)  

### Breaking change  
- New APIs used to enable single-sign-on options require connecting to [Mattermost server version 2.0 or later](https://github.com/mattermost/platform/blob/master/CHANGELOG.md)

## Release v1.0.0

Released 2015-12-14

### Release Highlights

- First release of Mattermost iOS app, a team communication service for sharing messages and files across PCs and phones, with archiving and instant search 
- Using the iOS app requires a Mattermost service to be set up, see https://github.com/mattermost/platform for more details
 
### Features

Push Notifications
- Ability to enable push notifications for mobile devices

Messaging and File Sharing

- Send messages, comments, files and images across public, private and 1-1 channels
- Personalize notifications for unreads and mentions by channel
- Use #hashtags to tag and find messages, discussions and files

Archiving and Search 
 
- Search public and private channels for historical messages and comments 
- View recent mentions of your name, username, nickname, and custom search terms

Anywhere Access

- Use Mattermost from a native iOS app as well as from web-enabled phones and PCs
- Define team-specific branding and color themes across your devices
