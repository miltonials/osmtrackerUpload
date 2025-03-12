name: "Pull Request"
description: "Submit a new feature or bug fix for OSMTracker."
body:
  - type: markdown
    attributes:
      value: |
        ## Thank you for your contribution!
        Please fill out the following details to help us review your pull request.

  - type: input
    id: pr_title
    attributes:
      label: "Pull Request Title"
      placeholder: "Briefly describe your PR..."
    validations:
      required: true

  - type: textarea
    id: pr_description
    attributes:
      label: "Description"
      description: "Provide a clear explanation of the changes in this PR."
      placeholder: "Describe what this PR does and why it's needed."
    validations:
      required: true

  - type: input
    id: related_issues
    attributes:
      label: "Related Issues"
      description: "Link to the original bug report or related work (if applicable)."
      placeholder: "e.g., Closes #123 or Related to #456"
    validations:
      required: false

  - type: checkboxes
    id: pr_checklist
    attributes:
      label: "Pull Request Checklist"
      description: "Please confirm the following before submitting your PR:"
      options:
        - label: "The PR is proposed to the proper branch."
          required: true
        - label: "The changes have been tested on different Android versions."
          required: true
        - label: "Automated tests have been added (if applicable)."
          required: false
        - label: "The feature is well documented."
          required: true
        - label: "There is a reference to the original bug report and related work."
          required: false
