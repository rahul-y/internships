---
layout: page
permalink: /guidance/students-accepted/
title: Advice for accepted students
---

First of all, welcome to InterMine! We're excited to have you working with us this year.

We'll try to generally adhere to the [Google Manuals](https://developers.google.com/open-source/gsoc/resources/guide) to avoid repetition, but here are a few InterMine-specific guidelines for Google Summer of Code.

## Communication

You'll establish a personal rhythm with your mentor, but please bear the following points in mind:

### Email

All students and mentors should subscribe to our [InterMine GSoC public mailing list](https://lists.cam.ac.uk/mailman/listinfo/gen-intermine-gsoc-public). This is to ensure that we can effectively share announcements.

### Chat

You can come hang at [chat.intermine.org](http://chat.intermine.org) in the #gsoc channel, and feel free to ask for help in #support - but remember to make tickets or send emails for any big bugs or design decisions, as chat logs are transient.

### Videoconferencing

Most of our students met via videoconferencing software, e.g. Skype, once every one or two weeks. You may need to meet more (or less!) often throughout the project life cycle.

## Writing code

### Quality

All code must be to a high standard, documented and well-commented, and accompanied by a unit test (where applicable).

### Source Control

We use GitHub for our source control, with a [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/)-like branching model. New work is done in personal forked repo branches,  periodically merged into the upstream dev branch when it appears stable.  master contains only stable releases merged from dev.

You should follow a similar model - treat `github.com/intermine/yourproject` as upstream and work on a branch your own fork, i.e. `github.com/yourusername/yourproject`, merging (or PRing for existing projects) periodically. Remember, pushed commits (to your own repo or InterMine's) prove you're alive and working on the project! ;)

We'll fork your repo so there will always be an InterMine upstream.

### Licence

If you're starting a brand new project, think about what **licence** you'd like.  It needs to be open source, obviously, but so long as it's a permissive open source licence like Apache, MIT, BSD, or LGPL, we'll probably be happy. Discuss it with your mentor before committing to a licence.

## Project Management

1. It's okay not to use the workplan from your proposal, but you and your mentor will need to agree to any changes.
2. You do need a workplan! Make sure you and your mentor have a good idea of what the deliverables are.
3. You'll want to schedule regular meetings with your mentor.

### Time commitment / Missed days

From the [Google Manual](https://developers.google.com/open-source/gsoc/resources/guide):


>GSoC needs an investment of about 30 hours a week. If you know in advance that you’ll need to take a couple of days of vacation/break during the Summer of Code, you should communicate that with your mentor beforehand and plan to make up for lost days.

## Outreach

We'd love to host blog posts about yourself, the work you're planning to do, or work you have done. Equally, if you're tweeting or blogging on a personal blog and would like us to link to it / mention you / etc., poke your mentor and we'll give you a shout-out.

## Final Report

Each student will present their project at the end of August at the InterMine Community Call - a friendly teleconference call attended by the InterMine community -- developers and biologists who use InterMine. The presentation will be limited to 5 minutes with a short time available for discussion after. Ideally this will be a live demonstration of your software project but can be slides or video demo instead. 

Each student will also write up their project. This will take the form of a short blog post with the following sections:

* Summary of project goals 
  * Briefly restate what was in your project proposal.
* Summary of project achievements
  * What did you achieve?
  * Screenshots and code snippets are a good idea!
  * Acceptable to point to your other blog posts.
  * Link to final tool, GitHub URL etc.
* Self assessment 
  * What could you have done better? Lessons learned?
  * What are you particularly proud of?
* Future work
  * If you could work on your project longer, what features would you like to see added?
  * What's left to do?

This blog post will be "permanent" and will be used to submit to Google as your work product.
