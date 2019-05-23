Closes: 

 ### Pre-deployment checklist

- [ ] Before merging to master, verify that the code can be deployed on the day. Code that cannot be immediately deployed should not be merged
- [ ] Code tested on the local docker development environment before PR created and merged to master 
- [ ] Cross-browser testing on Chrome and cross-device testing (where appropriate)
- [ ] Cross-browser testing on Firefox and cross-device testing (where appropriate)
- [ ] Physical device - Cross-browser testing on IE and cross-device testing (where appropriate)
- [ ] Physical device - Cross-browser testing on Edge and cross-device testing (where appropriate)
- [ ] Testing environment (local or staging) confirmed up to date with the latest stable branch changes, dependencies (including other repositories and services), and database data
- [ ] PR reviewer confirmed code running on a testing environment (local or staging) before a merge
- [ ] Sign off (a PR approval) that the change does what is required
- [ ] Sign off (a PR approval) that the change is operationally fit for purpose (follows the finder tech stack,  infrastructure pattern)
- [ ] Sign off (a PR approval) that appropriate tests have been run
- [ ] For [medium impact changes](https://finder.atlassian.net/wiki/pages/resumedraft.action?draftId=579437491#Releasechecklist-releaseriskcalculation), slack communications have been sent to relevant stakeholders (e.g. Product manager, Product owner, Engineering lead, Team channel) before a release
- [ ] For [high impact changes](https://finder.atlassian.net/wiki/pages/resumedraft.action?draftId=579437491#Releasechecklist-releaseriskcalculation), a pre-deployment email has been sent to [all@finder.com](mailto:all@finder.com) 24h prior
- [ ] If deployment outside of support hours (standard support hours are Mon-Thurs 9AM - 3PM local time), sign-off from a principal, lead, or manager has been gained
- [ ] Support confirmed from deployer (at least for 2h post-deployment)
