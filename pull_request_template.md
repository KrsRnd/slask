# What does this MR do?

<!-- General overview and reasoning description goes here -->

# UI Screenshots

<!-- Screenshots here if applicable -->

# Any specific areas that need more careful reviewing?

# How can this be tested?

# Checklist

- [ ] All tasks for the story are completed
- [ ] Code adheres to guidelines (linting, prettier)
- [ ] Unit tests have been updated (if applicable)
- [ ] Merge from parent branch has been performed
- [ ] I have tested my code by running the code
- [ ] Any related documentation has been updated (e.g story info, wiki, readme)

# Auto tests

- [ ] run on branch
  1.  `npm run at-install-dep`
  2.  `npm run at-local-ci`

# Test heuristics checklist

https://confluence.se.axis.com/display/WEBTOOLS/Test+Heuristics

- [ ] Affected areas
- [ ] In offline mode
- [ ] Boundaries
- [ ] Error handling
- [ ] Different navigation points
- [ ] Interruptions (sign out, cancel)
- [ ] Backward compatible
- [ ] Different devices (use pia.axis.com to verify the result)
- [ ] Data sync
- [ ] Different languages, screen size
- [ ] Any external application affected by the changes
- [ ] Different browsers
- [ ] Different users
- [ ] Perform a common use case
- [ ] Responsiveness and performance
- [ ] Concurrency

# Before mergning

- See that the squash commit message at least contains the JIRA number
