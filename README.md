# MSM GUI

It's time to add a Graphical User Interface (GUI) on top of our APIs. **Here is the target we're trying to build:**

https://msm-gui.matchthetarget.com/

**Keep it open in a tab.** It's easy to get lost without having our goal in sights. Don't get confused between your app and the target, though; the tab title and favicon should help.

First, read through the code that we're starting with. A good sequence to read through is always:

 - `config/routes.rb` — get a sense of the API (the surface) of the application
 - `app/controllers` — see what logic is going on in each action
 - `app/models/` — get a sense of the tables and business logic (the heart) of the application

You'll see that we're starting at the ending point of MSM API.

## Standard Workflow

 1. Add dummy data to your database: `rails dev:prime`
 1. Start the web server by running `bin/server`.
 1. As you work, remember to keep `/git` open in a tab and **commit often as you work.**

## Handy HTML references

 - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a
 - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul
 - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/dl
 - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/hr
 - https://developer.mozilla.org/en-US/docs/Glossary/Entity
    - https://dev.w3.org/html5/html-author/charref
 - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table
 - https://developer.mozilla.org/en-US/docs/Web/HTML/Element/select
