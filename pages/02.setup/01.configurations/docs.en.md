---
title: Configurations
taxonomy:
    category:
        - docs
---

The Kunena Configuration feature allows users to tailor Kunena's functions to their specific site needs.  This feature allows, for example, users to decide what they will call their forum page, whether forum messages can be posted by anonymous users or only by registered users of the site, and whether other third-party components (like private messaging) are to be used.  Many of the choices can be made according to individual tastes; some, however, may cause unexpected consequences if they're not handled correctly.

As a general guide, the default settings that ship with Kunena's installation kit will be adequate for most purposes.

#### Basics
This article describes how to change the Kunena configuration parameters.

##### Accessing the Kunena Configuration feature
Go to the Kunena Backend and select the Kunena Configuration feature.

##### Configuration Page
There are two basic functions: Save and Restore Default.

Save function

- Any changes become effective by clicking the 'Save' button located at the top left of the page.

Restore Default function

- This restores the default configuration parameters for Kunena.

#### List of settings
The settings are arranged in the groupings listed below.  The default/initial values are settings that are supplied with a clean installation of Kunena.  If a previously-installed version of Kunena or Fireboard had been installed on the user's site, the old values will be preserved.<br>

New versions of Kunena may add or remove items in the list below.  Please check your version of Kunena.

#### General

##### Basic Settings

Forum Title
Initial/default value:  Kunena

Forum E-mail Address
Initial/default value:  Empty

Send E-mails to Users
Initial/default value:  Yes

Forum Offline
Initial/default value:  No

Forum Offline Message
Initial/default value:  The Forum is currently offline for maintenance. Check back soon!

Read Only Mode
Initial/default value:  No

Session Lifetime
Initial/default value:  1800

Enable RSS feed
Initial/default value:  Yes

Enable Debug Mode
Initial/default value:  No

Use English On Missing Strings
Initial/default value:  Yes

Display Page Creation Time
Initial/default value:  Yes

##### SEO Settings

Search Engine Friendly URLs
Initial/default value:  Yes

Direct Component Access
Initial/default value:  No

Support Legacy URLs
Initial/default value:  Kunena 1.x

##### Caching Settings

Caching
Initial/default value:  Yes

Cache Time
Initial/default value:  1 minute

---

#### Frontend

##### Look and Feel

Topics Per Page
Initial/default value:  20

Messages per page
Initial/default value:  6

Search Results
Initial/default value:  15

Show History
Initial/default value:  Yes

History Limit
Initial/default value:  6

Message Time Format
Initial/default value:  22 hours 13 minutes ago

Hover Message Time Format
Initial/default value:  27 Sep 2015 23:30

Show New posts
Initial/default value:  Yes

Show Announcement
Initial/default value:  Yes

Show Avatar on Category Index and Recent Topics
Initial/default value:  No

Show Moderators in Category Index
Initial/default value:  Yes

Category Legacy Image Path
Initial/default value:  category_images

Show Sub-Category Image
Initial/default value:  Yes

Enable Category Jump
Initial/default value:  Yes

Message Reporting
Initial/default value:  Yes

Reply Numbering Inside Topic
Initial/default value:  Show Real Post ID

Hide IP Addresses From Moderators
Initial/default value:  Yes

Category Filter in Recent Topics
Initial/default value:  Show Categories

Category List in Recent Topics
Initial/default value:  Show All Categories

Selectable Topic Icons
Initial/default value:  Yes

Enable Lightbox for Images
Initial/default value:  Yes

Recent Topics Time Period
Initial/default value:  Month

Default topic layout
Initial/default value:  Flat

Force users to pickup a category
Initial/default value:  No

Choose how to display article by default
Initial/default value:  Intro

Message Ordering
Initial/default value:  Oldest Post First

Search Time
Initial/default value:  A Year Ago

Let users edit the subject
Initial/default value:  Yes

Allow rating
Initial/default value:  No

Number of characters from start for shorten filename
Initial/default value:  0

Number of characters from end for shorten filename
Initial/default value:  14

#### Users

##### User Related

Display User Name
Initial/default value:  Yes

Require E-mail
Initial/default value:  No

Show E-mail
Initial/default value:  No

Show User Statistics
Initial/default value:  Yes

Show Karma Indicator
Initial/default value:  Yes

Enable Thank You Feature
Initial/default value:  Yes

Visible Thank You Limit
Initial/default value:  10

User Edits
Initial/default value:  Yes

User Edit Time
Initial/default value:  0

User Edit Grace Time
Initial/default value:  600

Show Edited Mark Up
Initial/default value:  Yes

Allow Favorites
Initial/default value:  Yes

Check Shadow Topic Box
Initial/default value:  No

Show Banned Reason
Initial/default value:  No

Display profile tab to manage attachments
Initial/default value:  Yes

User can report himself
Initial/default value:  Yes

Define if you want to log action or moderation
Initial/default value:  No

Show user status
Initial/default value:  Yes

##### Subscriptions

Email Header Image
Initial/default value:  /media/kunena/email/hero-wide.png

Allow Subscriptions
Initial/default value:  Yes

Plain Text Emails
Initial/default value:  No

Include Post Contents
Initial/default value:  Yes

Category Subscriptions
Initial/default value:  E-mail New Posts

Topic Subscriptions
Initial/default value:  E-mail Every Update

Check Subscription Box
Initial/default value:  Yes

E-mail to Multiple Recipients
Initial/default value:  0

E-mail Recipient Privacy
Initial/default value:  Hide Other Recipients (BCC)

Visible E-mail Recipient
Initial/default value:  Empty

---

#### Security

#####Security Settings

Allow Guests to Post/Write
Initial/default value:  No

Moderate Guests
Initial/default value:  No

Allow Guests to see Userlist
Initial/default value:  Yes

Allow Guests to see User Profiles
Initial/default value:  Yes

Registered Users Only
Initial/default value:  No

Moderate New Users
Initial/default value:  0

User Can Delete Own Post
Initial/default value:  Never

Show Deleted Messages
Initial/default value:  Administrators Only

Flood Protection
Initial/default value:  0

E-mail Moderators
Initial/default value:  Unapproved Posts

E-mail Administrators
Initial/default value:  Unapproved Posts

IP Address Tracking
Initial/default value:  Yes

Allow Guests to see Stats link
Initial/default value:  Yes

Max Links in message
Initial/default value:  6

Hide Replies For Guests
Initial/default value:  No

Prevent posting topic or reply with URL in title
Initial/default value:  No

Allow moderators to permdelete
Initial/default value:  No

##### CAPTCHA Configuration

Display Captcha for :
Initial/default value:  Registered Users

CAPTCHA Challenge for Users
Initial/default value:  0

##### Stop Forum Spam Configuration

API key
Initial/default value:  Empty

---

#### Avatars

##### Avatar Settings

Allow Avatar Upload
Initial/default value:  Yes

Use Avatars Gallery
Initial/default value:  Yes

Max. Avatar File Size
Initial/default value:  2048

Avatar Quality
Initial/default value:  75%

Avatar Resize Method
Initial/default value:  Interpolation (Better - Fast)

Avatar Cropping
Initial/default value:  No

---

#### Uploads

##### Attachments

Limit Attachments
Initial/default value:  8

Protect Attachments
Initial/default value:  No

Enable utf8 characters on attachments
Initial/default value:  Yes

##### Images

Allow Image Uploads
Initial/default value:  Registered Users

Show Images for Guests
Initial/default value:  Yes

Allowed Image Types
Initial/default value:  jpg,jpeg,gif,png

Check MIME Types
Initial/default value:  Yes

Legal MIME Types
Initial/default value:  image/jpeg,image/jpg,image/gif,image/png

Maximum Image File Size
Initial/default value:  150 kB

Maximum Image Width
Initial/default value:  800 px

Maximum Image Height
Initial/default value:  800 px

Thumbnail Width
Initial/default value:  32 px

Thumbnail Height
Initial/default value:  32 px

Image Quality for JPG Resizing
Initial/default value:  50%

##### Files

Allow File Uploads
Initial/default value:  Registerd Users

Show Attachments for Guests
Initial/default value:  Yes

Allowed File Types
Initial/default value:  txt,rtf,pdf,zip,tar.gz,tgz,tar.bz2

Maximum File Size
Initial/default value:  120 KB

---

#### Ranking

##### Ranking Settings

Ranking
Initial/default value:  Yes

Use Rank Images
Initial/default value:  Yes

---

#### BBCode

##### BBCode Settings

Disable Emoticons
Initial/default value:  No

Show Spoiler Tag in Editor Toolbar
Initial/default value:  Yes

Show Video Tag in Editor Toolbar
Initial/default value:  Yes

Show eBay Tag in Editor Toolbar
Initial/default value:  Yes

Trim Long URLs
Initial/default value:  Yes

Front Portion of Trimmed URLs
Initial/default value:  40

Back portion of trimmed URLs
Initial/default value:  20

Auto-Link URLs
Initial/default value:  Yes

Auto Embed YouTube Videos
Initial/default value:  Yes

Auto Embed eBay Items
Initial/default value:  Yes

Auto Embed Soundcloud Items
Initial/default value:  Yes

Enable Code Highlighting
Initial/default value:  No

Display Images With Non-standard File Extensions
Initial/default value:  Text

eBay Widget Language Code
itial/default value:  en-US

eBay Affiliate ID
Initial/default value:  5337089937

eBay AppID key
Initial/default value:  Empty

The Twitter consumer key
Initial/default value:  Empty

The Twitter consumer secret
Initial/default value:  Empty

Google maps API key to get better stats usage of google API
Initial/default value:  Empty

---

#### RSS

##### RSS Settings

RSS Feed type
Initial/default value:  By Topic

RSS Specification
Initial/default value:  RSS 2.0

RSS History (timelimit)
Initial/default value:  1 month

RSS Limit
Initial/default value:  100

Include Categories
Initial/default value:  Empty

Exclude Categories
Initial/default value:  Empty

Render HTML & BBCode in RSS feeds
Initial/default value:  Yes

Author Format
Initial/default value:  Name

Render Author in Title
Initial/default value:  Yes

Limit Number of Characters Per Item
Initial/default value:  All

Use Oldstyle Titles
Initial/default value:  Yes

Caching Interval
Initial/default value:  15

The URL of the basic RSS feed into FeedBurner
Initial/default value:  Empty

---

#### Extra

##### Userlist Settings

Users Per Page
Initial/default value:  30

Online Status
Initial/default value:  Yes

Display Avatar
Initial/default value:  Yes

Show Number of Posts
Initial/default value:  Yes

Show Karma
Initial/default value:  Yes

Show E-mail
Initial/default value:  No

Show Join Date
Initial/default value:  Yes

Show Last Visit Date
Initial/default value:  Yes

Show Profile Hits
Initial/default value:  Yes

Hide Super Users in user list
Initial/default value:  No

Online Users Contains
Initial/default value:  By time

Online Users Time Limit
Initial/default value:  1800

##### Statistics Settings

Show Who is Online
Initial/default value:  Yes

Show Statistics
Initial/default value:  Yes

Show General Statistics
Initial/default value:  Yes

Show Popular User Statistics
Initial/default value:  Yes

Number of Popular Users
Initial/default value:  5

Show Popular Subject Statistics
Initial/default value:  Yes

Number of Popular Subjects
Initial/default value:  5

Show Popular Poll Statistics
Initial/default value:  Yes

Number of Popular Polls
Initial/default value:  5

Show Popular Thank You Statistics
Initial/default value:  Yes

Number of Popular Thank Yous
Initial/default value:  5

User Count Contains
Initial/default value:  All Real Users

##### Poll Settings

Enable Polls
Initial/default value:  Yes

Maximum Number Poll Options
Initial/default value:  4

Time Between Consecutive Votes
Initial/default value:  00:15:00

Maximum Number of Votes Per User
Initial/default value:  100

Single Vote Only
Initial/default value:  Yes

Show Voters
Initial/default value:  Yes