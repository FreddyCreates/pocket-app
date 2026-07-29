# POCKET App (for users)

<p align="center"><img src="docs/brand/pocket-mark.svg" width="100" alt="POCKET"/></p>

This hub is the **user-facing front door**.  
Full host product source: **[FreddyCreates/pocket](https://github.com/FreddyCreates/pocket)**.

No secrets live here — only public links and how you open a seat.

---

## Download / open

| | |
|--|--|
| **Windows (Electron)** | [Latest release](https://github.com/FreddyCreates/pocket/releases/latest) |
| **Cloud desk (browser)** | Your operator’s URL, e.g. `https://pocket.medinatechlabs.net/desk` |
| **Edge app** | Open the desk in Edge → ⋯ → Apps → Install this site as an app |

---

## First open (user client)

When you launch the **user** app (not the owner shortcut):

```text
┌─────────────────────────────────────┐
│  Welcome to POCKET                  │
│                                     │
│  ○ Team / cloud desk   (most users) │
│  ○ This computer hosts POCKET       │
│  ○ Custom URL                       │
│                                     │
│           [ Continue ]              │
└─────────────────────────────────────┘
         │
         ▼  (if cloud / custom)
┌─────────────────────────────────────┐
│  Desk URL: https://…                │
│  [Back]            [ Open POCKET ]  │
└─────────────────────────────────────┘
         │
         ▼
   Desk loads → Create my seat or Sign in
```

| Choice | What happens |
|--------|----------------|
| **Team / cloud** | You paste the operator’s public URL. App checks the desk is up, then opens `/desk`. |
| **This computer** | App starts (or reuses) a local host on this PC if the product is installed. |
| **Custom URL** | Same as cloud, any `https` origin your team gave you. |

**Saved on device:** only which source + desk URL.  
**Never saved by the shell:** passwords, seat keys (`pk_seat_…`), API keys.

Next time you open the app, it goes straight to your saved desk.  
Change later: app menu → **Change desk source…**

---

## Create your seat (multi-user)

1. Operator mints a **seat invite key** (`pk_seat_…`) — not their password.
2. You open the desk → **Create my seat**.
3. Paste the key, choose **your** username and password.
4. Next time: sign in as **you**. You are not the owner account.

---

## What POCKET is

Real multi-agent desk on a host PC: coding agents, cowork/desktop embodiment, sovereign git vault, API.

## Links

- Product source: https://github.com/FreddyCreates/pocket  
- Multi-user docs: https://github.com/FreddyCreates/pocket/blob/main/docs/MULTI_USER.md  
- Ship guide: https://github.com/FreddyCreates/pocket/blob/main/docs/SHIP_FOR_USERS.md  

© ItsNotAI Labs
