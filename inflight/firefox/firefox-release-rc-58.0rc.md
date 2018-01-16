# firefox 58.0rc

### Date of go-to-build: 2018-01-15

## Preflight tasks (pre go-to-build)
- [x] 1. due:2018-01-15 - [bug 1415557](https://bugzil.la/1415557): this is actually a post gtb human task but we are limited in rw and can't create ad-hoc tasks until after gtb. We should merge, fix conflicts of the patcher patch we have needed since 57.0. Context: https://bugzilla.mozilla.org/show_bug.cgi?id=1415557#c9 and recent example tools patch with required retagging can be found here: https://bugzilla.mozilla.org/show_bug.cgi?id=1421535#c8 *Note*: we still need proper docs on how to do this I believe.

## Build 2  

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/cynEWCkRSZyGzr5qg_6fTA)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish in Balrog on beta channel
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 4.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page (bug 1428419)
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish release tasks
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug 1430535](https://bugzil.la/1430535)        | Despite backout of bug 1418425 and CDN purge in bug 1430597, we got CRC errors for partials | False | True |
| nthomas  | 2 | [bug 1415557](https://bugzil.la/1415557)        | Update verify failures from testing updates from behind the watersheds at 57.0.4 (linux & mac) and 56.0 (win) | False | True |
| jlund  | 3 | [bug 1430670](https://bugzil.la/1430670)        | AWS network issues causing lot's of failures over the network. Tasks need to be rerun. Something like: https://irccloud.mozilla.com/pastebin/LulhGcoq/ | False | True |

## Build 1  :bomb: _aborted release. starting new build num_ :bomb: 

### Graphs
[task group](https://tools.taskcluster.net/push-inspector/#/HQFXrJxVQbi-Rqcpv41Thw)


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [ ] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish in Balrog on beta channel
- [ ] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog
- [ ] 4.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Updates_through_Shipping#Set-up_whatsnew_page)  - setup whatsnew page (bug 1428419)
- [ ] 5.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [ ] 6.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#publish-the-release)  - publish release tasks
- [ ] 7.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/wiki/Release-Promotion-Tasks#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| nthomas  | 1 | [bug 1430535](https://bugzil.la/1430535)        | Despite backout of bug 1418425 and CDN purge in bug 1430597, we got CRC errors for partials | False | True |
| nthomas  | 2 | [bug 1415557](https://bugzil.la/1415557)        | Update verify failures from testing updates from behind the watersheds at 57.0.4 (linux & mac) and 56.0 (win) | False | True |
