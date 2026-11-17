# Zenorun End User License Agreement

Version: 2026-11-08

Zenorun is © 2026 Hexsis Enterprise LLC. All rights reserved, except as this agreement grants.

This agreement is between Hexsis Enterprise LLC ("we") and the person or organization that installs or runs Zenorun ("you"). In this agreement, Zenorun means the Zenorun software: the service image (controller, allocator and web dashboard), the runner images and their documentation. By installing or running Zenorun you accept this agreement. If you do not accept it, do not install or run Zenorun.

## 1. License

We grant you a non-exclusive, non-transferable license to install and run Zenorun on servers you control, for your own organization's work, within the limits of your license key. We keep all other rights. Zenorun is licensed, not sold.

## 2. License keys

- Every install needs a license key. Without one, Zenorun schedules no jobs.
- A key is for one GitHub organization and one server. It names its tier, its licensed vCPU (runners configured × vCPU per runner) and, for a dated key, its end date. You must not run a key on more than one server at a time, or run more licensed vCPU than the key allows. The only exception is Zenorun's own fallback: when a key ends or its license is revoked, or a new key allows fewer licensed vCPU than you have configured, Zenorun keeps one runner of each runner profile even if that goes over the limit, so your jobs keep running. The exception does not let you add runners or profiles above the limit.
- **Free tier:** one free key per GitHub organization, for one host and up to 8 licensed vCPU, with the features the free tier lists at https://zenorun.com/pricing. A free key does not expire.
- **Paid and custom licenses:** a Pro subscription or a custom license gives the tier, licensed vCPU and term it states. When it ends, Zenorun falls back to the free tier's limits after its grace period. If we revoke it, because a payment for it was disputed or refunded in full, other than a refund of a charge made by mistake, Zenorun falls back to the free tier's limits once it hears of the revocation, whatever the key's dates. Running jobs are not stopped.
- You get keys from our customer portal. Do not share a key outside your organization.

## 3. What you must not do

You must not, and must not let anyone else:

- copy, sell, rent, sublicense or redistribute Zenorun, its images or its keys, except to run it as section 1 allows;
- reverse engineer, decompile or disassemble Zenorun, except as far as the law lets you despite this restriction;
- remove, bypass or tamper with the license check, a key's limits, or any notice in Zenorun.

## 4. Third-party software

Zenorun contains third-party software under its own licenses, listed in `THIRD_PARTY_NOTICES.md` in the service and updater images and the notices in each runner image. Those licenses, not this agreement, govern that software, and nothing here limits your rights under them. `SOURCE_OFFER.md` says how to get the source code of components under the GPL or LGPL.

Using Zenorun with GitHub is subject to GitHub's own terms, which you must follow.

## 5. Contact with us

Zenorun runs on your servers and does not send us your jobs, code or logs. It contacts us for one thing: an optional daily check that collects a renewed key, or hears that the license was revoked, on by default and off with one setting. The runners also talk to GitHub, as every runner does, to pick up jobs and send each job's step logs.

## 6. Runner images and support

- **Runner images.** From version 1 of Zenorun onward, we publish a new runner image within 7 days of each release of GitHub's Actions runner, and within 2 days of one that fixes a security issue or that GitHub makes the minimum version.
- **Support.** Support is through issues on our public distribution repository at https://github.com/zenorun-hq/zenorun/issues, or by email to support@zenorun.com, on a best-effort basis. A contract you sign with us may add other support and a service level.

## 7. No warranty

Zenorun is provided "as is", without warranty of any kind, express or implied, including fitness for a particular purpose and non-infringement. We do not promise that it is free of errors or that it will run without interruption. No license includes a service level unless a contract you sign with us states one.

## 8. Limit of liability

To the extent the law allows, we are not liable for indirect, incidental, special or consequential damages, or for lost profits, revenue or data. Our total liability under this agreement is limited to the greater of the fees you paid us for Zenorun in the 12 months before the claim and USD 100.

## 9. Feedback

If you send us feedback or suggestions, we may use them without obligation to you.

## 10. Ending this agreement

This agreement lasts while you run Zenorun. It ends automatically if you break it. When it ends, stop running Zenorun and delete its images and keys. Sections 3, 7, 8, 10 and 11 continue after it ends.

## 11. General

This agreement is governed by the laws of the State of Wyoming, United States, where Hexsis Enterprise LLC is registered, and the courts of Wyoming decide any dispute. We may update it; a new version applies to releases published after its date. Questions: legal@zenorun.com, Hexsis Enterprise LLC, 542 Washington Ave 18, Miami Beach, FL 33139, USA.
