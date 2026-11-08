# Security

Please don't report a security vulnerability in a public issue.

## Report a vulnerability

Report it privately, in either of these ways:

- **On GitHub:** [report a vulnerability](https://github.com/zenorun-hq/zenorun/security/advisories/new) through this repository's private vulnerability reporting. Only you and Zenorun can see the report.
- **By email:** write to [security@zenorun.com](mailto:security@zenorun.com).

In the web UI, Help › Report a security issue links to both.

This covers Zenorun's service image, its runner images and the install files in this repository.

## What to include

- The Zenorun version. Help › About in the web UI shows it.
- What you found, and what an attacker could do with it.
- The steps to reproduce it, and anything you used to show it, such as a workflow file or a request.

Leave out secrets: license keys, GitHub App credentials, tokens and the values in your `.env` file. A support bundle has them removed, so you may attach one. [What the support bundle holds](https://zenorun.com/docs/support-bundle) lists everything in it.

## Supported versions

We fix security issues in the latest release. To get a fix, upgrade to the release that carries it.

## What happens next

We reply within 3 business days to confirm that we have your report, and keep you told as we look into it and fix it. When the fix is released, we publish a security advisory in this repository.

There is no bug bounty.

For anything that isn't a security issue, see [Contact](https://zenorun.com/contact).
