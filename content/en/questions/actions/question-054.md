---
question: "When creating custom GitHub Actions - in what file does all the action `metadata` have to be defined?"
title: "Question 054"
---


Metadata examples: name, description, outputs or required inputs
> https://docs.github.com/en/actions/creating-actions/metadata-syntax-for-github-actions
1. [x] In the `action.yml` or `action.yaml` file in the action repository
1. [ ] In the repository `README` file
> While it's good practice to do that, it's not a requirement for the action to work
1. [ ] It's edited in GitHub Marketplace UI when published for sharing
1. [ ] In the `action.yml` or `action.yaml` file in the action repository, but it is not required if the action is not meant to be shared and used by the public
> All actions require the metadata file.
