<div align="center">
  <img src="https://hooktap.me/hooktap-logo.png" alt="HookTap" height="48" />
  <br /><br />
  <strong>Your iPhone as a webhook receiver. In real time.</strong>
  <br />
  Send an HTTP POST — HookTap forwards it instantly as a push notification, widget, or Live Activity.
  <br /><br />

  [![App Store](https://img.shields.io/badge/App_Store-iOS-black?style=flat-square&logo=apple)](https://apps.apple.com/app/hooktap/id6670671021)
  [![Website](https://img.shields.io/badge/hooktap.me-website-red?style=flat-square)](https://hooktap.me)
  [![Integrations](https://img.shields.io/badge/integrations-open_source-orange?style=flat-square&logo=github)](https://github.com/HookTap/hooktap-integrations)
  [![GitHub Action](https://img.shields.io/badge/GitHub_Action-notify--action-2088FF?style=flat-square&logo=githubactions&logoColor=white)](https://github.com/marketplace/actions/hooktap-notify)
</div>

---

```bash
curl -X POST https://hooks.hooktap.me/webhook/YOUR_ID \
  -H "Content-Type: application/json" \
  -d '{"type":"push","title":"Deploy complete","body":"v1.4.0 is live"}'
```

**That's it.** Your iPhone gets a notification in seconds.

---

## What HookTap does

HookTap gives you a personal webhook URL. Anything that sends an HTTP POST — a CI pipeline, a cron job, a script, a no-code tool — can reach your iPhone instantly. No server, no account, no waiting.

- **Push notifications** — lock screen, Dynamic Island, Live Activity
- **Home & Lock screen widgets** — always-visible status at a glance
- **Desktop apps** — macOS and Windows companion apps
- **JSON Mapping** — map any payload shape to a notification without changing your sender
- **Webhook Sharing** — share webhooks with teammates

## Available on

| Platform | |
|---|---|
| iPhone | Free & Pro · [App Store](https://apps.apple.com/app/hooktap/id6670671021) |
| Mac | Pro · [hooktap.me](https://hooktap.me) |
| Windows | Pro · [hooktap.me](https://hooktap.me) |

## Repositories

| Repo | Description |
|---|---|
| [notify-action](https://github.com/HookTap/notify-action) | GitHub Action — one step to send iPhone notifications from any workflow |
| [hooktap-integrations](https://github.com/HookTap/hooktap-integrations) | Open-source recipes — Python, Node.js, Shell, Docker, Zapier, and more |
| [hooktap-landing](https://github.com/HookTap/hooktap-landing) | Marketing site (Next.js, public for transparency) |

---

<div align="center">
  <a href="https://hooktap.me">hooktap.me</a> · <a href="mailto:mail@hooktap.me">mail@hooktap.me</a>
</div>
