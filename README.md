# Open Source Standards and Conventions

[![Filament Group](http://filamentgroup.com/images/fg-logo-positive-sm-crop.png) ](http://www.filamentgroup.com/)

## Repository Maintenance

### Repository States

* _Active_: the default, if unspecified a repository is in this state.
* _Unmaintained_: Code is still in a workable state but unsupported and not responding to new issues or accepting any new pull requests.
    * [Example](https://github.com/filamentgroup/jQuery-Equal-Heights)
* _Retired_: Code should not be used. Approach has been deprecated or folded into another repository. Also has the properties of being unmaintained (per above).
    * [Example](https://github.com/filamentgroup/face-off/)

### Process to update repository status

1. Prepend the following to the the GitHub repository description:

> Unmaintained (see README):

> Retired (see README):

2. Add a note to the project README:

```markdown
# ⚠️ Unmaintained: SocialCount
# 🚫 Retired: SocialCount
```

```markdown
Per [our unmaintained repository status documentation](https://github.com/filamentgroup/standards-and-conventions/blob/master/repository-maintenance.md#unmaintained) this repository is in an as-is state and is no longer accepting issue reports or pull requests.
```

3. Close active issues and pull requests, you can use the following response template:

> Unfortunately this repository has been moved into an unmaintained state and as such all open issues and pull requests will now be closed. The content there-in has been deprecated in favor of [LINK TO NEW CONTENT HERE]().

> Unfortunately this repository has been moved into an retired state and as such all open issues and pull requests will now be closed. The content there-in has been deprecated in favor of [LINK TO NEW CONTENT HERE]().

4. Switch the repository to an Archived state in GitHub settings.

5. Update related blog posts with the following notice:

> The techniques described in this blog post have been deprecated in favor of [LINK TO NEW CONTENT HERE]().
