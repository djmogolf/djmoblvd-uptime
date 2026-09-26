# DJ Mo Blvd — uptime check

Every 5 minutes GitHub checks that https://book.djmoblvd.com (Encore) answers.

- If it's down after 3 tries, this repo opens an issue titled **"book.djmoblvd.com is down"** — GitHub emails you about it, and a failed run emails you too.
- When it's back, the issue is closed with a comment, so you get a "back up" email.

Nothing private lives here: it only loads the public site. To pause it, open the
Actions tab → Uptime → "…" → Disable workflow.
