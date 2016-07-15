# Repository Maintenance

## Repository States

### Active

Default, if unspecified a repository is in this state.

### Unmaintained

Code is still in a workable state but unsupported and not responding to new issues or accepting any new pull requests. [Example](https://github.com/filamentgroup/jQuery-Equal-Heights)

#### Process to update the repository

* Update the GitHub repository description to the following:

> This repository has been retired. Please see the included readme for more information.

* Close active issues, you can use the following response template:

> Unfortunately this repository has been moved into an unmaintained state and as such all open issues and pull requests will now be closed. The content there-in has been deprecated in favor of [LINK TO NEW CONTENT HERE]().

* Update related blog posts with the following notice:

> The techniques described in this blog post have been deprecated in favor of [LINK TO NEW CONTENT HERE]().

### Retired

Code should not be used. Approach has been deprecated or folded into another repository. Also has the properties of being unmaintained (per above). [Example of a Retired respository](https://github.com/filamentgroup/face-off/)