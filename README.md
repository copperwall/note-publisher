Note-Publisher
==============

A project to improve my ability to record and review notes

### The Process

I've recently started taking notes on my netbook through vim, however, I wanted an easy way to make them slightly more readable and accessible from anywhere. I decided that I would start taking notes using markdown, and then convert the markdown to HTML in order to review them. This solved the readability problem, so I made a little bash script that will publish to my home server, allowing the notes to be viewed anywhere with an internet connection.

### What's complete

* Publishing script, which takes markdown files, converts to HTML, and transfers to my home server.

### What is coming

* I would like to build a webapp that can organize these notes through a UI, possibly one that is dynamically generated based on the notes files that exist on the server.

### Dependencies

* Bash
* [Markdown] (http://daringfireball.net/projects/markdown)
* Rsync
