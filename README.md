# Qwik Evolution

This is the place for new proposals and ideas for the Qwik framework. 

## Introduction

This following outlines the process for proposing, discussing, and implementing new features and substantial changes to the Qwik framework. The goal is to ensure that new features align with Qwik's core values and community needs while maintaining a transparent and collaborative approach.

A lot of changes like bug fixes and docs updates can be handled by a normal pull request and do not require this process.

But some changes have a wider effect and require design and discussion to make sure their impact will be positive for the wider Qwik community and will stay true to Qwik's philosophy.

In the Qwik Evolution process, timelines can vary—from days or weeks on urgent matters to much longer for non-urgent but high-value improvements.

## Qwik RFC Process


### STAGE 1 - Proposal 

A proposal is any change suggestion or feature idea for Qwik

🧑 **Who can create it?**

Anyone from the Qwik community can create a new proposal.

✨ **How to create one?**

Create a [proposal discussion using the suggested template](https://github.com/QwikDev/qwik-evolution/discussions/new?category=proposals)

📃 **Checklist for becoming a "RFC Issue":** 

- [x] Detailed and well articulated Proposal
- [x] Accepted via a Core leadership team vote
- [x] Has at least one champion from the core team

.

### STAGE 2 - RFC Issue

An RFC issue is a Github issue that's based on the original proposal discussion.
This means the implementation exploration can be started and all related PRs should be linked in that issue.
An RFC is led by champions from the Core team but the original proposal submitter could join as a community champion to provide help / insight / feedback during the exploration process. 

🧑 **Who can create it?**

Core team member

📃 **Checklist for advancing to the review stage:** 
- [x] Full implementation of the proposal
- [X] All the changes are covered by tests
- [x] No unresolved critical discussions left on the issue

.

### STAGE 3 - RFC Implementation Review

The RFC related Pull requests should be reviewed and fully tested before 

🧑 **Who can create it?**

Any contributor can help with the implementation of the RFC, with coordination with the core team

📃 **Checklist for approving the implementation:** 
- [x] At least 2 reviewers from the core team
- [x] The necessary documentation for the feature / change is added


.

### STAGE 4 - Developer preview

The PR is merged and is released under either a feature flag or a special alpha version.

📃 **Checklist for releasing it as stable** 
- [x] A period of at least 30 days of testing with community partners to gather feedback and fix bugs

.

### STAGE 5 - Stable feature

RFC Issue is closed and moved to `Released as Stable (STAGE 5)`.

Oh happy days! 😊🎉

.

#### Credit

This process was inspired by: [TC39](https://github.com/tc39/proposals), [Astro](https://github.com/withastro/roadmap), [Ember](https://github.com/emberjs/rfcs).
