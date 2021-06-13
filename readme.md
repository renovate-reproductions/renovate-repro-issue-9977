## Reproduction repository for Renovate issue 9977

### Current behavior

Renovate tries to remediate the trim security vulnerability, but fails.
The Renovate Dashboard keeps showing the trim security vulnerability in the "Open" section.
There is no open branch for the trim security update, and there is no error message, or way to dismiss the stuck vulnerability update.

Renovate does open PRs and branches for other security updates, so the basic mechanism is working.

### Expected behavior

Renovate raises a error message in some way to let me know that it cannot remediate the vulnerability.
It then allows me to dismiss the trim update in the Renovate Dashboard.
