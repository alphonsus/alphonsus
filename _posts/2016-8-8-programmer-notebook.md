---
layout: post-with-cover
title:  "Making A Programmer Notebook App #1"
categories: electron
comments: true
---

Hello. Starting today I will be "devlogging" my process on making a programmer notebook app.

### The Problem

I take down programming notes and cheat sheets a LOT on my Mac's Notes app. It usually looks like this:

![](/images/prog-notebook/1.png)

While it usually gets the job done, look at that mess. It definitely just isn't meant to be a "programming notebook."

My issues with using Notes app as an app to take down programming notes:

- A not-monospace font. While we _can_ edit the font manually, it takes several keystrokes and clicks. And that's _everytime_ we make a new note, since at the time of writing there is no way to set the default font. We need a monospace font right off the bat.
- No markdown support.
- Tags/categories feature. Yes we can organize notes into folders, and I do use that. But sometimes I also want notes to have multiple tags/categories, which I can then filter.

Things I do like about the Notes app are:

- Auto-saving. I don't have to open notes from files, or save new notes into files, then open them again when I need to.
- It syncs across all my Apple devices.
- It's just really easy and efficient to use in general. Just create a new note, type stuff in, use some hotkeys to change the format (e.g. Cmd+Shift+H to set to Heading), close the app, open it again, continue where you left off, etc. No need to click save buttons or type in the Note title and stuff.

### The Solution

So that's where this I'll-be-making-a-programming-notebook-app thing comes in—an attempt to create a Notes-esque app but more programmer-centric. I'm envisioning it as a markdown editor but with all the nice features we love in Notes.app. And hey, this will be a perfect excuse for me to finally start learning Electron!

### ...Electron?

![](/images/prog-notebook/2.png)

[Electron](http://electron.atom.io) is a framework to create native applications using web technologies. Atom, Slack, Visual Code Studio, among others are all made with this framework. I've always wanted to try and make something with it ever since I heard about it earlier this year. I will be using it for this project given my familiarity with creating web apps as opposed to creating native macOS apps.

On my next post(s) I will talk about my current progress with the development and a mini-tutorial on how to get started with creating Electron apps. Here's the project's [source code](https://github.com/AlfonzM/markdown-editor). Be warned, I am not the best modern-JS coder! And I will probably be porting this and use an actual JS framework like React in the future, depending on how large the project gets.