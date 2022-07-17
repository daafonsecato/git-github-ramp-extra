# 8 Completed Release

| Date | Phase |
| --- | --- |
| February 28<sup>th</sup> | Release |

It is the last day of the month and no more requests have come in from the, time to push the code to production and merge changes to the release back into the `develop` branch.

## :running: Activities

### 1 - Merge Release Branch into `main` and `develop`

__Maintainers__

Choose a maintainer to merge `release/1.1.0` into `main`.

```sh
$ git flow release pull v1.1.0

$ git flow release finish v1.1.0

$ git checkout main

$ git push

$ git checkout develop
```

:bulb: Always make sure that `develop` is up to date before merging. There may be some merge conflicts that will need to be addressed at this point.

Choose a maintainer to push the the commit up to the fork repository:
```sh
$ git push origin develop
```
---

:cop: :raised_hand: - Please wait until everyone has caught up.

:construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction: :construction:

---

### 3 - Create a Release tag in GitHub

Choose a maintainer to create a Release in GitHub:

1. On the fork repository page, click the "# releases" link in the stats bar at the top (or append `/releases` to the repo URL).
2. Click new release.
3. Name the release tag v1.1.0, choose the main branch, and document the changes comprising the release.

The release feature in GitHub is an easy way to keep track of changes associated with each release. Files may also be uploaded and attached to the release, so they can also act as a place to store any additional files related to the release that are not tracked in version control.


## :tada: We're done!

You did it! Feel free at this time to navigate around the fork repository, yours and others' forks and reflect back on all the hard work that was done to get v1.1.0 out the door :sunglasses:.

## Quick Links

- [Readme](../readme.md)
- [1. Setup](1-setup.md)
- [2. Feature Branches](2-feature-branches.md)
- [3. Code Review](3-code-review.md)
- [4. Fetching the Latest](4-fetching-latest.md)
- [5. Hotfix](5-hotfix.md)
- [6. Release Branch](6-release-branch.md)
- [7. Release Bugs](7-release-bugs.md)
