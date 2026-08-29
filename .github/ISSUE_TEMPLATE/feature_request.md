name: Feature request
description: Suggest an idea or enhancement for Booksmith or DarkQuill
labels: ["enhancement"]
body:
  - type: markdown
    attributes:
      value: |
        We appreciate your feedback and feature suggestions!
  - type: dropdown
    id: application
    attributes:
      label: Target Application
      options:
        - Booksmith Studio (Desktop)
        - DarkQuill Reader (Android)
    validations:
      required: true
  - type: textarea
    id: problem
    attributes:
      label: Is your feature request related to a problem?
      placeholder: A clear and concise description of the problem.
  - type: textarea
    id: solution
    attributes:
      label: Describe the solution you would like
      placeholder: A clear description of what you want to happen.
    validations:
      required: true
