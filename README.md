# DDM
Draft Data Manual Can be browsed at: [andjnewman.github.io/DDM/](http://andjnewman.github.io/DDM/)

### About this manual

This site has been developed to test the suitability of Github Pages and Jekyll as a platform for the publication of guidance on the design, sharing and use of data across Defra group.

Whilst the site itself is an alpha and may change please use the alpha/beta indicators to understand the status of the guidance published here. If there is no indicator on the page the content is finalised.

## Format:

- This site is built using the Jekyll framework and Github Pages
- The content for the site is written in markdown
- The content is stored in markdown '.md' files the in the 'framework', 'guides' and 'standards' folders.
- Each .md file has a header containing metadata, this is used to render the pages, the format for this header is shown below
  - Note this is not finalised and may change!
  - For Categories, Roles, Status, Phases delete values as required.

```
---
layout: default
title: 1. Understand data needs
subtitle: |
  Research to develop a deep knowledge of: the outcome, the data subject, potential users and their needs.
type: guide
categories: [principles, framework, lifecycle, guides]
roles: [Everyone, Analysts, Data Managers, Data Owners, Data Architects]
status: alpha, beta, final
phases:
  - Need
  - Check
  - Obtain
  - Store
  - Share
  - Use
  - Archive
breadcrumbs:
  -
    title: Home
    url: /DDM
  -
    title: Principles
    url: /DDM/framework/principles
---
```

