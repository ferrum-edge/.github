# Security policy

This is the default security policy for repositories in the
[ferrum-edge](https://github.com/ferrum-edge) organization. A repository with
its own `SECURITY.md` uses that file instead. Its supported versions and scope
take precedence over this one.

## Reporting a vulnerability

Please do not report a security problem in a public issue, discussion, or pull
request. Don't disclose it publicly before a fix is available.

Report it privately in one of two ways:

1. **GitHub private vulnerability reporting.** In the affected repository, open
   the **Security** tab and choose **Report a vulnerability**. The direct link
   is `https://github.com/ferrum-edge/<repository>/security/advisories/new`.
   This is the preferred channel wherever the button is shown.
2. **Email** **contact@ferrumedge.com** if private reporting isn't available
   for that repository. Put "Security" in the subject line.

Please include:

- the repository and the affected version, tag, image, or commit;
- the configuration or deployment mode involved, if relevant;
- steps to reproduce, or a minimal proof of concept;
- the impact you believe the issue has.

Don't include live credentials, private keys, or tokens in a report.

## What happens next

We aim to acknowledge a report within **5 business days**. We'll keep you
informed through triage, the fix, and the release. Fixes are published through
GitHub Security Advisories on the affected repository. We credit reporters
unless you ask us not to.

## Supported versions

Unless a repository's own policy says otherwise, security fixes land on its
default branch and ship in its next published release. Older releases don't
receive backports. Upgrade to the newest release to get a fix.
