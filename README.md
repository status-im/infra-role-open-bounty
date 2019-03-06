# Description

This role configures Status [Open Bounty](https://github.com/status-im/open-bounty) service which sets bounties for GitHub issues and pais out Eth rewards.

# Usage

Made available at domain configured the `sob_domain` variable.
Currently only two installations exist:

* https://openbounty.status.im/ - `sob-test` host group.
* https://test-openbounty.status.im/ - `sob-prod` host group.

# Configuration

Configured via `host_vars`, for example configuration see [`ansible/group_vars/sob-test.yml`](/ansible/group_vars/sob-test.yml).
