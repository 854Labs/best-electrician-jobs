# Best Electrician Jobs

Manage your company's electrician job posts and applicants on
[BestElectricianJobs.com](https://www.bestelectricianjobs.com) from your AI assistant
or coding agent: draft and publish jobs, read résumés and move candidates through hiring.

This repository contains the plugin manifests. They connect to the hosted
Best Electrician Jobs MCP server:

```
https://www.bestelectricianjobs.com/mcp
```

Published by [854 Labs](https://github.com/854Labs). Listed in the
[Official MCP Registry](https://registry.modelcontextprotocol.io/v0/servers?search=com.bestelectricianjobs)
as `com.bestelectricianjobs/mcp`.

## Who it's for

Electrical contractors and other employers hiring electricians and apprentices. It
works with employer accounts only; job seekers find and apply to jobs on the website.

## What you can do

- See your posting overview, open job slots and how each job is performing.
- Turn a pasted job description into a private draft with trade categories, licences,
  certifications, pay and screening questions.
- Publish drafts, pause or unpublish live jobs, and resume paused ones.
- Review applicants by stage, open applications and read the text of attached PDF or
  Word résumés.
- Move applicants to Reviewed or Shortlisted, add private team notes, and reject or mark
  someone as hired.

Publishing a job, rejecting and hiring always need your approval first: Claude shows an
approval prompt, ChatGPT shows a card you tap Approve on, and other clients ask you to
confirm in chat. Everything else happens when you ask.

## Install

**Claude (web, desktop, mobile)**
Add a custom connector with the server URL above. See
[bestelectricianjobs.com/claude](https://www.bestelectricianjobs.com/claude).

**ChatGPT**
See [bestelectricianjobs.com/chatgpt](https://www.bestelectricianjobs.com/chatgpt).

**Other MCP clients**
Add a remote (Streamable HTTP) MCP server with the URL above. Your client opens a browser
window to sign in with your Best Electrician Jobs employer account.

## Sign-in and privacy

You sign in with your own Best Electrician Jobs employer account through OAuth and approve
the connection on our consent page. No API key is needed. You only ever see your own
company's jobs and the people who applied to them. You can disconnect at any time from
Connected apps in your account.

- [Privacy policy](https://www.bestelectricianjobs.com/infopages/privacy)
- [Terms](https://www.bestelectricianjobs.com/infopages/terms)

## Example prompts

- "What's my posting overview?"
- "Here's our job description. Turn it into a draft for a Journeyman Electrician in Austin
  at $38–45 an hour."
- "Which applicants still need review? Read the newest résumé and list the licences."

## Support

[support@bestelectricianjobs.com](mailto:support@bestelectricianjobs.com) ·
[Contact](https://www.bestelectricianjobs.com/contact)

## License

The manifests in this repository are MIT licensed. The Best Electrician Jobs name, logo
and hosted service are not covered by this license.
