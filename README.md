# FOSS Assertions

Apache 2.0 licensed fork of FluentAssertions taken from the upstream repository commits made directly before the licensing change.

This repository contains no versions or branches of fluent assertions that have been contaminated with the non-free licensing change.

# Current branches

- `main` - this is effectively the last v8 available in git before the license file was replaced
- `support-v7.0` most recent commit

# Tags of upstream commits

There were two branches of interest when the license was changed, the v7 support branch, and the new v8 branch. v8 was relicensed, and the time of creation of this fork v7 licensing had not been changed. The following tags have been created to make it easy to understand where this repo forked off and distanced itself from the upstream fluent assertions licensing debacle

- `last-apache-licensed-upstream` - this was upstream main (i.e. v8) at [the very last commit before the apache license was removed](https://github.com/fluentassertions/fluentassertions/commit/df7e9bf8305ef5e26ae58fe4142f8d1b6c4fc4af) from the upstream repo.
- `upstream-support-7.0` - the upstream v7 maintenance branch at the time this fork was created
