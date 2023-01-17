---
# Leave the homepage title empty to use the site title
title:
date: 2023-01-17
type: landing

sections:
  - block: about.avatar
    id: about
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      # Override your bio text from `authors/admin/_index.md`?
      text:  
    design:
      columns: '2'
  - block: collection
    id: featured
    content:
      title: Publications      
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation 
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      # Contact (add or remove contact options as necessary)
      email: 13477000139@163.com
    design:
      columns: '2'
---
