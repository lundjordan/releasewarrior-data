# firefox 61.0b3

### Date of go-to-build: 2018-05-07

## Preflight tasks (pre go-to-build)
- none

## Build 1  

### Graphs
* [promote](https://tools.taskcluster.net/push-inspector/#/bpgJFUOIReqo1AFZY2Vc4w) bpgJFUOIReqo1AFZY2Vc4w
* [push](https://tools.taskcluster.net/push-inspector/#/c6uqUd5MSkauX9P_CglMRw) c6uqUd5MSkauX9P_CglMRw
* [ship](https://tools.taskcluster.net/push-inspector/#/LirDe2hAQeurbWmOchrJRg) LirDe2hAQeurbWmOchrJRg
```
export PROMOTE_TASK_ID=bpgJFUOIReqo1AFZY2Vc4w
export PUSH_TASK_ID=c6uqUd5MSkauX9P_CglMRw
export SHIP_TASK_ID=LirDe2hAQeurbWmOchrJRg
```


#### Status
- [x] 1.  [how-to](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)  - submit to Shipit
- [x] 2.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#push-artifacts-to-releases-directory)  - pushed to mirrors/releases
- [x] 3.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#ship-the-release)  - schedule the release for shipping
- [x] 4.  [how-to](https://github.com/mozilla-releng/releasewarrior-2.0/blob/master/docs/release-promotion/desktop/howto.md#obtain-sign-offs-for-changes)  - signoff in Balrog

### Issues
| Who                 | ID               | Bug                                                                 | Description                | Resolved                | Future Threat                |
| ------------------- | ---------------- | ------------------------------------------------------------------- | -------------------------- | ----------------------- | ---------------------------- |
| asasaki  | 1 | [bug none](https://bugzil.la/none)        | beetmover-repackage-linux64-asan-reporter-nightly/opt shouldn't be part of the promote graph | True | False |
| asasaki  | 2 | [bug 1408868](https://bugzil.la/1408868)        | we removed too many bouncer config files | True | False |

