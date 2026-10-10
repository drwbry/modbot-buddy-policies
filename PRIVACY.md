# modbot-buddy Privacy Policy

**Effective date: October 10, 2026**  
**Last updated: October 10, 2026**

modbot-buddy (the “App”) is a Reddit Devvit application operated by u/drwbry.
It helps subreddit moderators by posting short AI-written summaries (“TL;DRs”)
of busy comment threads, and, if a community’s moderators turn it on, by sending
posts, summaries, and report alerts to that community’s own Discord server.

## Information the App processes

- **Public post and comment text.** When a thread reaches the configured comment
  count, the App reads the post’s title and text and the text and scores of its
  most-upvoted comments in order to write a summary. For the weekly digest, it
  reads the week’s top posts and a few of their top comments.
- **Community settings** chosen by the community’s moderators, such as the
  bot’s persona name, writing style, thresholds, the community’s Gemini API
  key, and any Discord webhook URLs. These settings are visible to that
  community’s moderators.
- **Operational records:** Reddit post and comment identifiers, the comment
  milestone each summary was written for, timestamps, and error messages, used
  to avoid duplicate summaries and duplicate Discord messages.
- **Report details**, only if Discord report alerts are turned on: the reported
  post or comment’s text excerpt, author username, link, and report reason.
- **Operational logs,** which may include community names, Reddit identifiers,
  and error information.

The App leaves out author usernames when it sends thread text to the AI
service, and it never uses comments that were removed by moderators or marked
as spam. It does not collect email addresses, passwords, private messages,
votes by individual users, precise locations, advertising identifiers, or
payment information. It does not use advertising or behavioral analytics.

## How information is used

Information is used only to:

- Write and post thread summaries and the optional weekly digest.
- Share posts, summaries, and report alerts to a community’s Discord server,
  when its moderators have turned this on.
- Prevent duplicate posts and messages, diagnose errors, and keep the App
  running.

## Storage and retention

The App stores only small operational records using Reddit Devvit’s hosted
storage. Summary-tracking records expire after 30 days, Discord sharing records
after 14 days, and report-alert records after 1 hour. The App does not store
post or comment text. Summaries the App posts remain on Reddit as ordinary
comments until a moderator removes them. Operational logs are subject to Reddit
Devvit’s hosting and retention practices.

Uninstalling the App stops its future activity. A moderator may contact the
operator to request deletion of App-controlled stored records.

## Third parties

The App runs on Reddit’s Devvit platform and is subject to Reddit’s platform
terms and privacy practices.

- **Google Gemini API** (generativelanguage.googleapis.com). Post and comment
  text, without author usernames, is sent to Google to generate summaries,
  using the Gemini API key that the community’s moderators provide. The App’s
  setup guide asks communities to use a paid key; under Google’s Gemini API
  terms for paid services, Google does not use prompts or responses to improve
  its products, and logs them for a limited time only to detect abuse and meet
  legal requirements. Reddit data is not used by the App or the operator to
  train any AI model.
- **Discord** (discord.com), only if a community’s moderators turn Discord on
  and provide webhook URLs. The App then sends post titles, links, author
  usernames, short text excerpts, summaries, and (for report alerts) report
  reasons to the Discord channels those moderators chose. Content in Discord is
  subject to Discord’s terms and privacy policy and to that server’s settings.

The App does not sell personal information and does not share information for
cross-context behavioral advertising.

## Security

The App uses Reddit Devvit’s hosted execution and storage services and limits
stored information to what its features need. A community’s Gemini API key and
webhook URLs are stored in Devvit’s app settings for that community. No method of storage or transmission can be
guaranteed to be completely secure.

## Your choices and requests

Community moderators control the App’s settings, can turn off summaries,
Discord, and the digest, can exclude individual posts, and can uninstall the App
at any time. If a moderator removes a summary, the App stops summarizing that
post. To ask a privacy question or request deletion of App-controlled data,
send a Reddit message to u/drwbry and identify the affected subreddit.

## Children

The App is not directed to children and does not knowingly collect personal
information from children. Use of Reddit remains subject to Reddit’s own age and
eligibility requirements.

## Changes to this policy

This policy may be updated if the App’s features or data practices change. The
effective date above will be revised when material changes are made.

## Contact

For privacy questions or requests, contact u/drwbry through Reddit.
