---
layout: page
title: Han Yang's Project Portfolio Page
---

### Project: TAilor

TAilor is a desktop app for managing contacts. The user interacts with it using a CLI, and it has a GUI
created with JavaFX. It is written in Java, and has about 10 kLoC.

Given below are my contributions to the project.

* **Code contributed**: [RepoSense link](https://nus-cs2103-ay2122s2.github.io/tp-dashboard/?search=festivecat&breakdown=true)

* **Enhancements implemented**:
  * **Feature 1**: Extending `Find` command [\#75]()
    * What it does:
      Originally: `Find` only allows users to search contacts in the database using names.
      Now, `Find` allows users to search contacts using names, studentNumber, tags, email etc. (All fields in a Person)
    * Justification:
      This feature improves the product significantly because it can be used to find and view the
      students/contacts easily. Makes the original command more robust.
    * Highlights:
      Incorporated many individual classes for each of the search conditions, as well as a compounded search condition
      that allows searching based on all conditions passed into it.
    * Time spent on this (estimate):
      210mins
  * **Feature 2**: Implementing `Mod` class [\#72]()
    * What it does:
      This is basically another field/detail about a person, like Name and Email.
    * Justification:
      This feature makes our application more targeted towards our target user, Teaching Assistants.
      By having this `Mod` class, Teaching Assistants can now tag students with a certain Class, ie `CS2030S`
      To better keep track of their students.
    * Time spent on this (estimate):
      150mins
  * **Feature 3**: Implementing the Task Manager [\#88]()
    * What it does:
      The task manager will help the target audience keep track of tasks for their students better.
      For example, a Teaching Assistant can use the task manager to keep track of when certain assignments are due,
      which allows them to contact their students if needed. <br>
      Additionally, users can also use this to keep track of their own personal tasks if they desire to do so.
    * Justification:
      This features allows our application to be more than just any contact management/contact list application.
      By incorporating this, the target audience now has an in-built feature to assist in their task-tracking activities.
      This feature can also be extended to be linked to Students, Mods or Groups. It can also be extended to use
      different priority systems to rank the Tasks, as well as a reminder system for upcoming tasks.
    * Time spent on this (estimate):
      900mins

* **Enhancements to existing features**:
  * Add Mod class/field (Pull request [\#72]())
  * Find command (Pull requests [\#75]())
  * Extended UI to include the task manager feature (Pull Requests [\#122]())
  * Bugfixes (Pull requests [\#111](), [\#136](), [\#207](), [\#212]())

* **Documentation**:
  * User Guide (UG):
    * Reviewed UG for v1.1, made minor formatting and grammatical changes.
    * Updated UG for parts I have modified/implemented/extended. In particular:
      * I included the extra search parameters that can be used in the Find Command.
      * I updated the `add`/`edit` commands to include `Mod`, as well as to add in the `Group` attribute
      * I also incorporated the new Task Manager commands, `newtask` and `deltask` and how they should be used.
    * I also added in additional sections on prefix usages, intended workflow and an extended introduction at the start
      of the document to better guide users along with how to use our application.
    * I also incorporated the link to table of contents under most major headings and subheadings
  * Developer Guide (DG):
    * Changed some "Address Book" into "Contact List" to better represent the project.
    * Updated DG for parts I have modified/implemented/extended.
      * In particular, I remade the Model and Storage UML diagrams (V2) to include the newly implemented Task Manager functionality.
      * There is also a section under "Implementations" that describes how the Task Manager interacts with the rest of TAilor.
    * I also incorporated the link to table of contents under most major headings and subheadings

* **Contribution to team-based tasks**:
  * Made team organisation and repository at the beginning.
  * Transferred half of User Stories into Issues to track.
  * Incorporated a standardised commit message format: [\#67]()
  * Vetted issues raised after the PE dry run to sort out duplicate or invalid bugs due to intentional design.

* **Project management**:
  * Drove team meetings forward, increasing productivity.
  * Up-kept a list of deliverables per week, updating it frequently so that everyone
  is on the same page.
  * After the initial pass for the issues rasied after PE dry run, organised them coherently and assigned them appropriately
    to the team.

* **Community**:
  * PRs reviewed (with non-trivial review comments):
  [\#42](), [\#46](), [\#52](), [\#64](), [\#85](), [\#93](), [\#94](), [\#95](), [\#97](), [\#98](),
  [\#102](), [\#107](), [\#108](), [\#110](), [\#114](), [\#116](), [\#117](), [\#119](), [\#123](),
  [\#125](), [\#128](), [\#211](), [\#213]()
