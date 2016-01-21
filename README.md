# Ideas

Some ideas I have for side projects and such. I've been keeping ideas in a few different places and never had a single place for them. Now I do.

These ideas are licensed under the MIT license (as though ideas could be copyrighted anyway) and you can feel free to do whatever you want with them. I just want them to exist! Preferably they would be free software (free as in both beer and liberty).

- **OS X/iOS Markdown Editor** - A quality, free Markdown editor with iCloud sync support, an iOS app, and a design based off [Letterspace](http://programmerbird.com/letterspace/). For taking notes and such things. Should be as minimal as possible, probably. Perhaps with better support for writing code, e.g. with GitHub Flavored Markdown. And probably with better tagging. The problem is making it so it doesn't get bloated (see: Evernote). Preferably you'd be able to disable as much as possible, maybe have an extension system?
- **Documentation Browser** - Like [Dash](https://kapeli.com/dash), but not bad. This app is such a great idea - documentation for storage offline - but the app (on OS X, not sure about iOS) frequently includes outdated docs, the workflow is abysmal, and it's not free.
- **Font Compare** - A typeface comparison tool for finding the right font to use in a logo, or for other design-y reasons. Like [Typecase](http://typecaseapp.com/) or [Fontbook](https://support.apple.com/en-us/HT201749), but easier to use and built specifically for that purpose. Also, completely 100% free and open source. Maybe have folders support (e.g. "Favorite Fonts", "Sans Serif Fonts") so you can save your favorite fonts for viewing later when you need to make another logo.
- **Lorem Ipsum Generator** - An improved version of [LittleIpsum](http://littleipsum.com/) (e.g. more granular choices and more options, but don't get overly complex).
- **PC Game Search** - A search engine for PC games. Source information from the fantastic PCGamingWiki. You would be able to find - for example - all games that have support for OS X, controllers, and local multiplayer.
- **Game Library Tracker** - Well-designed, more automated game library tracker. Think [The Backloggery](http://www.backloggery.com/) or [Grouvee](https://www.grouvee.com/), but with Steam/Xbox/PSN integration so you can automate the process. Also with better design.
- **Backpack** - Less-bad bookmarks. Right now I have a mess of folders for keeping all my GIFs together, all the tech resources I like, etc. I literally have a folder called "Well-Designed Websites" in Chrome with over 100 websites in it. [Pocket](https://getpocket.com/) doesn't really work for what I want to do, [Stache](http://getstache.com/) isn't free and isn't really updated, and [Google Stars](https://chrome.google.com/webstore/detail/bookmark-manager/gmlllbghnfkpflemihljekbapjopfjik?hl=en) was a huge letdown for me. It should have robust Search, Folders, and Auto-tagging built-in. Also some sort of syncing feature and integration with Chrome/Firefox via an extension.
- **LintCI** - "Linting" Tests for Continuous Integration, How this isn't a thing, I have no idea. [HoundCI](https://houndci.com/) exists, but it's not exactly what I want. I'd like it to have a free tier and be a feature of an existing CI solution (e.g. CircleCI or Codeship) Essentially, I want tests to come back and tell me if code has been added that doesn't follow a style guide.
- **Knowledge Base** - Free Knowledge Base/Support docs software, e.g. the Knowledge Base components of [Zendesk](https://www.zendesk.com/) or [Help Scout](https://www.helpscout.net/), probably as a Ruby gem of some sort. Markdown support, basic web editor, thumbs up/down "did this help?", simple feedback system, customizable CSS, ability to categorize Knowledge Base articles, etc.
- **TV Dashboard** - A simple web interface to manage text and images w/ simple animations (e.g. a "slideshow" with various events coming up) running on a loop on TV screens (from a single display or a handful of displays, to hundreds of displays across a company or campus). Inspired by the screens across campus at my college, where the software they used cost a few thousand dollars (seriously) for something that seems like a month-long side project for two or three developers. [Withboard](https://github.com/scopely/withboard) exists, but its license and tech stack are weird.

## Open source contributions
Open source is awesome, and designers and developers are sorely needed for a lot of projects. Here are some existing projects to contribute to:

- Literally anything regarding [Elixir](http://elixir-lang.org/) and [Phoenix](http://www.phoenixframework.org/). These are almost definitely going to replace Ruby on Rails for a lot of people in the future, so please make tools for them! e.g. linting (think [Rubocop](https://github.com/bbatsov/rubocop)) for HTML, CSS, JS, and Elixir code (preferably with autocorrect! please!), icon font/SCSS SVG icon variables generator, [Autoprefixer](https://github.com/postcss/autoprefixer) integration, [API Documentation plugin](https://github.com/droptheplot/apipony), i18n tools (see [i18n-tasks](https://github.com/glebm/i18n-tasks) for Rails), documentation generator ([RDoc](https://github.com/rdoc/rdoc), but pretty and also customizable and also preferably some sort of support for non-Elixir code, like CSS and JS).
- [GitLab](https://about.gitlab.com/) - Lots of potential! Good for if GitHub goes rogue.
- [Lime Text](http://limetext.org/) - Unless Atom gets a hell of a lot faster, or Sublime Text goes open source itself, LimeText is my only hope for replacing Sublime in the near future. Please, God, don't screw me on this.
- Add Spotify integration to [WavHead](https://noidedmedia.github.io/WavHead/).
