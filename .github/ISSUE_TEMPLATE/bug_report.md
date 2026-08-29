name: Bug report
description: Create a report to help us improve Booksmith or DarkQuill
labels: ["bug"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to report an issue!
  - type: dropdown
    id: application
    attributes:
      label: Application
      options:
        - Booksmith Studio (Desktop)
        - DarkQuill Reader (Android)
    validations:
      required: true
  - type: dropdown
    id: os
    attributes:
      label: Operating System
      options:
        - macOS (Apple Silicon)
        - macOS (Intel)
        - Windows 10/11
        - Linux (Ubuntu/Debian)
        - Linux (Fedora/Arch/Other)
        - Android
    validations:
      required: true
  - type: input
    id: version
    attributes:
      label: App Version
      placeholder: e.g. v0.8.0-alpha
    validations:
      required: true
  - type: textarea
    id: description
    attributes:
      label: Describe the bug
      placeholder: A clear and concise description of what happened.
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      placeholder: |
        1. Open Booksmith
        2. Create a new manuscript
        3. See error
    validations:
      required: true
