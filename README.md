# gh-show-url

A trivial extension to [`gh`](https://github.com/cli/cli) to show the current pull request's URL.

To install, check out, `cd` into the repo, and run `gh extension install .`

Requires [`jq`](https://github.com/jqlang/jq).

## Notes

This could have been an alias except for the `jq` part. Maybe it's possible to get rid of this?

There seem to have been requests for [this functionality](https://github.com/cli/cli/issues/601), or at least something similar, but given how easy this was to implement, they're probably right not to make this part of core.
