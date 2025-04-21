---
name: Submit a flag
about: Submit a flag request to the database
labels: 'flag-request'
assignees: 'jeanpantaleon'
body:
- type: input
  attributes:
    label: 'The author of the flag'
    placeholder: 'Your name'
  validations:
    required: true
- type: input  
  attributes:
    label: 'The name of the flag'
    placeholder: 'Your flag\'s name'
  validations:
    required: true
- type: textarea
  attributes:
    label: 'Your image'
---
