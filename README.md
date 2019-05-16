# Sekiro Cheat Sheet

To view the cheat sheet [click here](https://zkjellberg.github.io/sekiro-cheat-sheet)

## Contribution Guide

If you are interested in contributing to this guide, I welcome Pull Requests on GitHub.

**NOTE: This guide is currently in its early phases and will be evolving quickly.**

For some background on how the guide code is written, here is a sample item on the checklist:

```html
<li data-id="playthrough_13_20" class="f_gem f_misc">Continue left until you can enter a room with a Large Soul of a Nameless Soldier and a Raw Gem</li>
```

The **data-id** is a unique ID used to store the user's progress. For example, ***playthrough_13_20*** is the 20th task in zone 13. New data-ids must be used in ascending order, but you can place the new entries anywhere within a zone.

The **class="f_gem f_misc"** field is used for the filtering system. This task provides the user with a gem and a consumable, so we use **f_gem** and **f_misc**. This is a feature from the Dark Souls guide and will be revamped as the walkthrough is built.