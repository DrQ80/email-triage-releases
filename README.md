# Email Triage — releases

This repository holds the built copies of **Email Triage**, a Mac app that sorts
your inbox on your own Mac. The website is <https://getemailtriage.app>.

There is no source code here, only the files a release is made of:

| File | What it is |
| --- | --- |
| `Email-Triage-x.y.z.dmg` | the download: open it and drag the app to Applications |
| `Email-Triage-x.y.z.zip` | what an installed copy fetches when it updates itself |
| `latest.json` | the update notice an installed copy reads when you ask it to check |

`latest.json` is signed. The app checks the signature against a key built into it,
and checks the zip's SHA-256 against the signed notice, before it installs
anything. So a file here that was changed by anyone else is refused.

Questions go to support@getemailtriage.app.
