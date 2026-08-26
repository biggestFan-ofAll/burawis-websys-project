# 6kun

## Description

**6kun** is a dark, community-driven horror board built around the weird corners of the internet.

Users share creepypastas, paranormal encounters, urban legends, strange photographs, unexplained events, personal experiences, found media, half-remembered stories, and whatever else they think belongs in the archive.

It's part anonymous imageboard, part horror community, and part social archive. Some posts are serious. Some are jokes. Some are obviously made up. Some are harder to explain.

The site should feel like a place where people actually hang out—not a polished horror publication.

---

# Current Pages

## 1. Landing Page (`index.html`)

### Header

* 6kun logo + tagline
* Nav: Home, Login, Register

### Body

* Welcome section introducing 6kun as a place to share and archive strange stories
* "What is 6kun?" description
* Featured boards:

  * Paranormal
  * Urban Legends
  * Unexplained
* "Got something to share?" section
* Create Account / Login links

### Footer

* About
* Community Guidelines
* Privacy Policy
* Terms of Service
* Contact
* Copyright

---

## 2. Home Page (`home.html`)

The main logged-in landing page and the closest thing 6kun has to a front page.

### Header

* 6kun logo
* Search bar
* Nav:

  * Home
  * Boards
  * Trending
* Profile
* Logout

### Body

* Small moderator announcement / site notice
* "Post Something Weird" button
* Board list:

  * `/paranormal/`
  * `/urban-legends/`
  * `/unexplained/`
* Trending discussions
* Fresh threads from across the site

### Content Style

Threads should feel like they were actually created by different people.

Some users should:

* Write normally
* Post in lowercase
* Ramble
* Make jokes
* Argue with other users
* Be skeptical
* Take everything completely seriously
* Post obvious creepypasta
* Post genuine personal experiences
* Shitpost
* Disappear after making a strange post
* Become recurring users with recognizable personalities

The site should develop its own small community over time.

### Footer

* Community Guidelines
* Contact
* Help
* Copyright

---

# 3. Login Page (`login.html`)

### Header

* 6kun logo
* Back to 6kun

### Body

* Username or Email
* Password
* Keep me logged in
* Enter 6kun button
* Forgot password link
* New user → Make an account

### Tone

Keep this page simple.

It shouldn't feel like a horror-themed login screen. The site's personality should come from the wording, not excessive decoration.

### Footer

* Privacy Policy
* Terms of Service
* Copyright

---

# 4. Register Page (`register.html`)

### Header

* 6kun logo
* Back to 6kun

### Body

* Pick a Username
* Email
* Password
* Confirm Password
* Join 6kun button
* Existing user → Log in

### Tone

The page should feel like joining an established internet community.

"Already lurking?" is an appropriate bit of personality here.

### Footer

* Privacy Policy
* Terms of Service
* Copyright

---

# Planned Pages

## 5. Thread View (`thread.html`)

Displays an individual thread and its replies.

### Contains

* Board breadcrumb
* Thread title
* OP username
* Date/time
* Original post
* Replies
* Reply form

### Important

Threads should feel like conversations between actual users rather than scripted horror stories.

Replies can include:

* Genuine reactions
* Skepticism
* Jokes
* Corrections
* Personal anecdotes
* People asking for pictures/details
* Users recognizing old stories
* Users referencing other threads
* Occasional unsettling comments

Recurring usernames should be allowed to develop personalities and histories.

---

## 6. Category / Board Page (`category.html`)

Lists threads belonging to a particular board.

### Contains

* Back to Home
* Board name
* Short board description
* Create Thread button
* Recent threads

### Current Boards

`/paranormal/`

Ghosts, hauntings, strange houses, sleep paralysis, sightings, and things that shouldn't be standing in doorways.

`/urban-legends/`

Local folklore, childhood warnings, internet legends, chain stories, rumors, and things somebody's cousin swears happened.

`/unexplained/`

Strange photographs, recordings, missing time, weird coincidences, unexplained events, and things nobody can quite agree on.

### Board Culture

Each board should eventually develop its own regulars, running jokes, arguments, famous threads, and recurring subjects.

---

## 7. Create Thread Page (`create-thread.html`)

Form for creating a new thread.

### Fields

* Thread title
* Board
* Post body
* Submit button

### Wording

* "What's going on?"
* "Where does it belong?"
* "Tell us what happened"
* "Post It"

The form shouldn't imply that users need to submit professionally written horror stories.

A thread can be anything from a carefully written creepypasta to:

> "my neighbor has been standing outside my house every night"

---

## 8. User Profile Page (`profile.html`)

Displays a user's small corner of 6kun.

### Contains

* Username
* Join date
* Number of threads
* Number of replies
* Short bio
* Threads started by the user

### Profile Philosophy

Profiles should be intentionally minimal.

This isn't meant to become a conventional social-media profile.

A user's identity should mostly exist through their **posts**.

Over time, however, recurring users can become recognizable through:

* Their writing style
* Their usernames
* Their favorite boards
* Their running jokes
* Their previous threads
* Their interactions with other users

---

# Community Identity

6kun should feel like an actual internet community rather than a horror content website.

## User Types

The site should naturally contain different kinds of people:

### The Believers

Completely convinced that something supernatural happened.

### The Skeptics

Have a mundane explanation for absolutely everything.

### The Storytellers

Post elaborate creepypastas and fictional stories.

### The Lurkers

Rarely post but occasionally appear in a thread with one incredibly specific comment.

### The Shitposters

Turn every serious thread into a joke.

### The Archive Rats

Remember old posts, deleted threads, obscure usernames, and ancient site drama.

### The Tumblr Crowd

Write long personal posts, collect images, make connections between stories, and occasionally turn a random thread into something much larger.

### The Regulars

Recognize each other and slowly develop their own community history.

---

# Site Personality

6kun should not constantly announce that it is scary.

Avoid things like:

* "ENTER THE DARKNESS"
* "YOU SHOULDN'T BE HERE"
* "WELCOME TO THE NIGHTMARE"
* Excessive blood imagery
* Constant references to death
* Every thread sounding like a professionally written creepypasta

Instead, the horror should come from the **content and the people using the site**.

A normal conversation becoming strange is more effective than announcing that something is frightening.

For example:

> **motelghost:** probably nothing but my camera keeps taking pictures while it's turned off
>
> **salt_and_static:** battery issue maybe?
>
> **motelghost:** thought that too
>
> **motelghost:** then i took the battery out
>
> **deadchannel:** don't open the third one
>
> **motelghost:** what
>
> **deadchannel:** nothing

That kind of interaction should define 6kun.

---

# Backlog

Lower-priority pages and features:

* About
* Contact
* Community Guidelines
* Privacy Policy
* Terms of Service
* Help
* Forgot Password
* Search Results
* User Settings
* Edit Profile

---

# Future Features

Potential additions once the basic site is working:

* Image attachments
* Multiple images per post
* Anonymous posting
* Reply quoting
* Thread bumping
* Thread pagination
* Thread subscriptions
* User following
* Reblog-style sharing
* Tags
* Post reactions
* Saved threads
* Search
* Recently viewed threads
* Deleted-post placeholders
* Moderation tools
* Reports
* User bans
* Board-specific rules
* Archive of older threads

---

# Core Design Goal

**6kun should feel like a website that already existed before you found it.**

There should be old stories people remember.

There should be usernames that regulars recognize.

There should be arguments nobody remembers how they started.

There should be posts that were deleted.

There should be jokes that don't make sense unless you've been around.

There should be threads that are obviously fake.

There should be threads that everyone assumes are fake until someone posts something they shouldn't know.

And occasionally, there should be something genuinely unsettling sitting quietly between completely ordinary posts.

**The website isn't the horror story.**

**The people using it are what make the archive interesting.**