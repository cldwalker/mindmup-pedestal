## Description

This is a pedestal service that allows you to create a mindmap using
[keyboard shorcuts](http://blog.mindmup.com/p/keyboard-shortcuts.html)
and [mindmup's javascript](https://github.com/mindmup/mindmup). This
app *doesn't save a mindmap* so don't get attached.

A demo [lives on heroku](http://mindmup-pedestal.herokuapp.com/).

## Getting Started

1. Start the application: `lein run`
2. Go to [localhost:8080](http://localhost:8080/) and create a mindmap!

## Configuration

To configure logging see config/logback.xml. By default, the app logs to stdout and logs/.
To learn more about configuring Logback, read its
[documentation](http://logback.qos.ch/documentation.html).

## Limitations
*Many*. Only the homepage let's you mindmap with javascript and even it has some rendering issues.

## Credits

@brandombloom did most of the work via some good vim macros. I'm just to blame for the idea.
