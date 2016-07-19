# Beta: Firefox 48.0b9

### Started: 2016-07-18

## Build 1

### Beta Graph
task graph url: unknown


#### Status
- [ ] [submit to Shipit](https://wiki.mozilla.org/Release:Release_Automation_on_Mercurial:Starting_a_Release#Submit_to_Ship_It)
- [ ] [emailed beta-cdntest](../how-tos/relpro.md#1-email-drivers-re-release-live-on-cdntest-channel)
- [ ] [publish in Balrog](../how-tos/relpro.md#3-publish-in-balrog)
- [ ] [post-release tasks](../how-tos/relpro.md#4-post-release-step)

### Issues
- The initial requested revision was android-only, so we had no desktop builds. Set the previous revision in ship-it
- Because b8 was skipped, the in-tree revision was not matching the revision in ship-it. Bumped the revision and pushed to beta.
- [Bug 1287665](https://bugzil.la/1287665): add-on-devel windows builds overwrote the opt build TC indexes (missing config variables). jlund landed a patch to fix it.

