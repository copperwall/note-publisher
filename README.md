Note-Publisher
==============

A project to improve my ability to record and review notes
Also an exercise in Ruby

### The Process

I've recently started taking notes on my netbook through vim, however, I wanted an easy way to make them slightly more readable and accessible from anywhere. I decided that I would start taking notes using markdown, and then convert the markdown to HTML in order to review them. This solved the readability problem, so I made a little ruby script that will publish to my home server (or local machine), allowing the notes to be viewed anywhere with an internet connection.

### What's complete

* Publishing ruby script, which takes markdown files, converts to HTML, and transfers to my home server.

### What is coming

* I would like to build a webapp that can organize these notes through a UI, possibly one that is dynamically generated based on the notes files that exist on the server.
*  The current ruby script uses shell commands to transfer and convert markdown files to html. It would be nice to do that completely in ruby. There's a github-markdown gem that I can probably use.

### Dependencies

* Ruby 
* [Markdown] (http://daringfireball.net/projects/markdown)
* Rsync
