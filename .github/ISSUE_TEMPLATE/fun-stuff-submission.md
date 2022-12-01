---
name: issue_template
description: Share Fun Stuff
title: "Fun Stuff Submission"
labels: "Add FunStuff"
assignees:
 - shannonrankin
 - Kourtney-Burger
body:
  - type: input
    attributes:
      label: Title of your Fun Stuff
      description: Give a short, concise, and meaningful Title
      placeholder: ex. Violin Plot Compositions
    validations:
      required: true
  - type: textarea
    attributes:
      label: Brief Description
      description: Give a brief but helpful summary of what this fun stuff does
      placeholder: ex. Creates a musical composition from your data violin plots
    validations:
      required: true
  - type: input
    attributes:
      label: Link
      description: provide a URL link to your Fun Stuff
      placeholder: ex. www.making-music-from-violin-plot-data-like-a-pro.com
    validations:
      required: true
  - type: input
    attributes:
      label: Keywords
      description: Provide keywords to help us search for this again!
      placeholder: ex. music data violin 
    validations:
      required: true
  - type: textarea
    attributes:
      label: Additional Info
      description: Provide additional useful links such as Blogs, Videos, etc
      placeholder: ex. San Diego Youth Symphony plays your favorite climate change data (www.youtube.com/sdyscc20222xy)
    validations:
      required: false
  - type: markdown
    attributes:
    value: "Add an image! Pictures are Pretty"
 ---
