# HelvetiCan theme for TaskPaper 3

This is a simple port and polishing of my HelvetiCan Taskpaper 2.x theme to work
with the new [Taskpaper 3](http://taskpaper.com).

![](https://raw.githubusercontent.com/wakatara/HelvetiCan-Taskpaper-theme/master/HelvetiCan_taskpaper_theme_preview.png)

I probably use Taskpaper much differently than most people. I organize things
weekly, so make heavy use of an `@week(week_number)` tag which I find helps me
manage and control the many tasks I have flow-wise and that need triaging in
terms of priority and sequencing -- as well as easily moving things into the
future (as one of the main things I need to do is followup with people on
tasks or things they said they'd do.).

So, I tend to make heavy use of searches like `@week = 45 and not @done` to
look at all my tasks organized by client/project, picking a task, updating it
based on actioning it, and then moving it into a future week for followup
(ie. tagging the item with `emailed 2016-11-07 - fup @week(47)`). This works
*very* well for me.

This theme helps keep me focused and colour codes the things that are critical
for me as well as tracking things in process so I can just focus on what needs
to be done next and making sure nothing slips through the cracks or falls off
the edge of the world (or to someone I delegated to.).

## Featuring

- Lighter black for all default text items
- Nice heading titles for Projects and smaller subtitles for subprojects
- Green tag for when items are added ie. `@new(yyyy-mm-dd)`
- Moves entire item to green when started with the `@wip` tag ie
  `@wip(yyyy-mm-dd)`
- Red tag for items with a due date `@due(2016-12-25)`
- Red for items tagged `@today`
- Links for email or urls within an items are in a nice, clickable blue
- Tags are in a not-in-your-face grey so they do not distract from item text
- Notes are in a slightly darker grey to provide contrast but distract from item
  text
- Recommended items are in blue with a nice `@reco` tag (I have lots of lists)
- `@done(yyyy-mm-dd)` items are greyed out and a line runs through them
- `@cancel(yyyy-mm-dd)` items just end up being greyed out

I do not use `@priority` or various other tags and removed `@waiting` since anything
not done is waiting on someone or something to happen and I manage that with
my default search `@week(x) and not @done`.

## Installation

1. On the CLI or in Finder go to `cd ~/Library/Containers/com.hogbaysoftware.TaskPaper3/Data/Library/Application Support/TaskPaper/StyleSheets`
2. Copy `HelvetiCan.less` to the folder
3. Change TaskPaper StyleSheet by TaskPaper 3 menu: `Window > StyleSheet >
   HelvetiCan.less`

An easy way to open the Container-buried Stylesheet folder is to use the
application's Taskpaper 3 menu item `Window > Stylesheet > Open Stylesheet
folder`


## TODO

- Font - Not completely convinced Helvetica Neue is the optimal font for
  readability and information density, so experimenting a bit there. Please feel
  free to change `@font-family` in the stylesheet and let me know if you find a
  distinct readability or "density scanning" advantages to another font
- Better testing - I've only tested this on my new Macbook 12" early 2016
  edition which has a different screen resolution than MBAs and Pros. Information
  density on that screen is good, but curious about other people
- Notes don't automatically align with the text below their item. Trying to
  figure out how to sort that out to asve people time.
- Highlighting for +Name - I have to delegate or note people contacted a *lot*,
  so have a system where I add +Name to items to denote who was relevant. I am
  still trying to figure out how to highlight that in an item well under TP3 and
  have it used as a Search predicate for when I do updates with my staff. .
  Anyone who knows who I may accomplish this, please let me know.

## Contributing

Please feel free to raise any issues or PRs in the Github Issues section for bugs or
ways to improve the theme for everyone. Pull requests obviously very welcome.

