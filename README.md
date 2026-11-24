# Interview Feedback page (static copy)

Static copy of the Interview Feedback page, hosted here only so a Zoho Recruit Web Tab can frame it
(Zoho Catalyst blocks framing). It holds no data or keys: everything loads from the Catalyst function
after the person signs in with a code sent to their Cliq.

Source of truth: `recruit-interviewer-feedback/feedback-page/catalyst/functions/ifbpage/page.html` in the
private pulse-whatsapp repo. To update, copy that file here as `index.html` and push.

## /pipeline/ — Hiring Pipeline (read-only)
Static copy of `recruit-interviewer-feedback/hiring-page/page/index.html`. Signs in with Zoho (popup) through
the Catalyst function `hirepage`; all data is read from Recruit with the signed-in person's own access.
