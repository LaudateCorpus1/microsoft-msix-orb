# Microsoft MSIX orb

[![CircleCI Build Status](https://circleci.com/gh/CircleCI-Public/microsoft-msix-orb.svg?style=shield "CircleCI Build Status")](https://circleci.com/gh/CircleCI-Public/microsoft-msix-orb) [![CircleCI Orb Version](https://badges.circleci.com/orbs/circleci/microsoft-msix.svg)](https://circleci.com/orbs/registry/orb/circleci/microsoft-msix) [![GitHub License](https://img.shields.io/badge/license-MIT-lightgrey.svg)](https://raw.githubusercontent.com/CircleCI-Public/microsoft-msix-orb/master/LICENSE) [![CircleCI Community](https://img.shields.io/badge/community-CircleCI%20Discuss-343434.svg)](https://discuss.circleci.com/c/ecosystem/orbs)


Easily build Microsoft MSIX packages within your CircleCI pipeline.

## Resources

[CircleCI Orb Registry Page](https://circleci.com/orbs/registry/orb/circleci/microsoft-msix) - The official registry page of this orb for all versions, executors, commands, and jobs described.
[CircleCI Orb Docs](https://circleci.com/docs/2.0/orb-intro/#section=configuration) - Docs for using and creating CircleCI Orbs.

### How to Contribute

We welcome [issues](https://github.com/CircleCI-Public/microsoft-msix-orb/issues) to and [pull requests](https://github.com/CircleCI-Public/microsoft-msix-orb/pulls) against this repository!

### How to Publish
* Create and push a branch with your new features.
* When ready to publish a new production version, create a Pull Request from _feature branch_ to `master`.
* The title of the pull request must contain a special semver tag: `[semver:<segement>]` where `<segment>` is replaced by one of the following values.

| Increment | Description|
| ----------| -----------|
| major     | Issue a 1.0.0 incremented release|
| minor     | Issue a x.1.0 incremented release|
| patch     | Issue a x.x.1 incremented release|
| skip      | Do not issue a release|

Example: `[semver:major]`

* Squash and merge. Ensure the semver tag is preserved and entered as a part of the commit message.
* On merge, after manual approval, the orb will automatically be published to the Orb Registry.


For further questions/comments about this or other orbs, visit the Orb Category of [CircleCI Discuss](https://discuss.circleci.com/c/orbs).

