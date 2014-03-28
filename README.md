# Bites
The Good Eggs developer blog.


Why blog?
---------

**Notoriety**  
Our blog, open source software, and developer events are all opportunities for us
to establish Good Eggs as a _tech company_ in addition to a revolutionary local food company.

**Reinforce the [Manifesto](https://github.com/goodeggs/bites/blob/master/src/documents/posts/2014-02-25-manifesto.html.md#we-believe)**  
"_We believe_ in the value of exploration and innovation." The blog is a platform to share what we learn and create.

**Develop Tech Talks for Conferences**  
Consolidating ideas into a blog post is most of the legwork for creating a compelling talk for conferences and other events!


What to blog about?
-------------------
* open source software we authored
* tools, services, and libraries we're using
* design patters and techniques we're using
* a developer event we held
* processes (daily standups, retrospectives, etc)
* cool tech you saw/heard/tried/read about/etc.

** Got an Idea? **  
[Open an issue](https://github.com/goodeggs/bites/issues/new) with the label `blog post idea` and summarize some of the keypoints that will make the post interesting. You or someone else on the team can write it later.

** Need an Idea? **  
Check the [open blog post ideas](https://github.com/goodeggs/bites/issues?labels=blog+post+idea&state=open) that haven't been written yet!

How to write a post?
--------------------

** Intro **  
Give the reader a concise overview of what they'll get out of the post. If it's a long post, create a table of contents.

** Pictures **  
Relevant pictures make a post a lot easier to digest.

**Code Examples**  
Always show some `code` if the post is about coding!

** Links **  
Talking about a library, tool, an event you went to, someone else's blog, etc? Try a [hyperlink](http://en.wikipedia.org/wiki/Hyperlink)!

** Summary **  
Sum it up. Take a stance. Give an opinion.


How to post a post?
-------------------
Install and fire up the development server

    > npm install
    > grunt dev

Add a new post to [src/documents/posts](https://github.com/goodeggs/bites/tree/master/src/documents/posts)

    > touch src/documents/posts/YYYY-MM-DD-your-post-slug.html.md

If it's your first post, create your author page in [src/documents/authors](https://github.com/goodeggs/bites/tree/master/src/documents/authors)

Check it out at `http://localhost:8000/your-post-slug` or just `grunt open:preview`.  It'll regenerate when you change the source files.

When it looks about right

    > grunt stage
    > cd release && git diff

If that checks out

    > grunt release


Want feedback before you post?
-----------------------
[Submit a pull request](https://github.com/goodeggs/bites/compare/) towards the issue you're writing about. This will give the team a chance to read it and give feedback before you publish.
