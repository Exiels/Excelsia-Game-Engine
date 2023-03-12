---
name: Feature request
about: Suggest an idea for this project
title: "[FEAT]"
labels: enhancement
assignees: ''

---

**Is your feature request related to a problem? Please describe.**
A clear and concise description of what the problem is. Ex. I'm always frustrated when [...]

**Describe the solution you'd like**
A clear and concise description of what you want to happen.

**Additional context**
Add any other context or screenshots about the feature request here.


name: Missing feature
description: Create a feature issue
title: '[Feature]: '
labels:
  - enhancement
body:
  - type: input
    id: featureName
    attributes:
      label: Feature name
    validations:
      required: true
  - type: textarea
    id: featuretype
    attributes:
      label: Describe the problem
      description: Tell us what the problem is
    validations:
      required: true
  - type: textarea
    id: featureContent
    attributes:
      label: Explain the feature 
      description: Tell us what we should add
    validations:
      required: true
  - type: checkboxes
    attributes:
      label: I read the Code Of Conduct
      options:
        - label: I read the Code Of Conduct and I comply to it
          required: true
