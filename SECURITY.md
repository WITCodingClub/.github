# Security Policy

This policy applies to every repository in the WIT Coding Club organization.

## Supported versions

Our projects are services and apps that we deploy from the `main` branch. We
fix security issues in the deployed version and on `main` only. We do not
patch old releases.

| Project | Deployed at |
| --- | --- |
| WIT Calendar backend and website | <https://calendar.witcc.dev> |
| WIT Calendar browser extension | The latest version in the browser extension stores |

## Report a vulnerability

Do not open a public issue, discussion, or pull request for a security issue.

### GitHub private reporting (preferred)

1. Go to the **Security** tab of the repository that has the issue.
2. Click **Report a vulnerability**.
3. Fill in the form and submit it.

Only you and the maintainers can see the report. For the WIT Calendar, use
these links:

- Backend and API: <https://github.com/WITCodingClub/calendar-backend/security/advisories/new>
- Browser extension: <https://github.com/WITCodingClub/calendar-extension/security/advisories/new>
- Website: <https://github.com/WITCodingClub/calendar-website/security/advisories/new>

### Email

If you cannot use GitHub, send an email about a WIT Calendar issue to
<calendarwit@gmail.com>.

You can also send an email directly to the core maintainers of the WIT
Calendar:

- <lambertl@wit.edu>
- <mayonej@wit.edu>

### Encrypted email

To encrypt a report, use the OpenPGP key for <mayonej@wit.edu>. Send the
encrypted email to that address.

- Key: <https://github.com/jaspermayone.gpg>
- Fingerprint: `00E6 43C2 1FAC 965F FB28  D3B7 14D0 D45A 1DAD AAFA`

The URL above can return more than one key. Use the key with this
fingerprint. Before you use the key, make sure that its fingerprint is the same
as the fingerprint above.

### What to include

- The repository, URL, or extension version that has the issue.
- The steps to reproduce the issue.
- The effect of the issue, for example the data that a user can see or change.
- Your name or handle, if you want us to credit you.

## What happens next

1. A maintainer tells you that we received the report.
2. We examine the issue and tell you if we can reproduce it.
3. We make a fix and deploy it.
4. We publish a GitHub security advisory when the fix is live. We credit you
   if you want credit.

We are a student club, so a reply can take longer during exams and breaks.

## Rules for security research

Do research in good faith. We will not take action against you if you obey
these rules:

- Use only accounts and data that you own. Stop and report when you get
  access to data of a different person.
- Do not do denial of service tests, spam, or social engineering.
- Do not test systems that the club does not operate. Wentworth Institute of
  Technology systems, for example LeopardWeb, Banner, and the school email,
  are not in scope. Google, Rate My Professors, and Cloudflare are also not in
  scope.
- Give us a reasonable time to fix the issue before you tell other people
  about it.
