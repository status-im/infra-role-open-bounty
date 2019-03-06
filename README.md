# __WARNING__

>:warning: __This repository is an archive of how Status Open Bounty used to be configured.__

# Description

This role configures Status [Open Bounty](https://github.com/status-im/open-bounty) service which sets bounties for GitHub issues and pais out Eth rewards.

# Usage

Made available at domain configured the `sob_domain` variable.
Currently only two installations exist:

* https://openbounty.status.im/ - `sob-test` host group.
* https://test-openbounty.status.im/ - `sob-prod` host group.

# Configuration

Normally configured via `host_vars`. You `prod` and `test` environments were configured in [`vars`](/vars) directory.
