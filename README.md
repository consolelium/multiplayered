<h1 align="center">
  <img width="1280" height="384" alt="Project banner" src="https://github.com/user-attachments/assets/2891f26f-8a12-40a1-9379-811b13decda2" />
  <br>
  <img alt="GitHub license" src="https://img.shields.io/github/license/fridgington/multiplayered?style=flat-square" />
  <img alt="Package version" src="https://img.shields.io/github/package-json/v/fridgington/multiplayered?style=flat-square" />
  <img alt="Code size" src="https://img.shields.io/github/languages/code-size/fridgington/multiplayered?style=flat-square" />
</h1>
<p align="center">
  An easy-to-use web panel for Meta Horizon that allows developers and game administrators to manage their online application in real-time, without all the fuss of limits and paid tiers.
</p>

## 👋 Introduction
**multiplayered** is a self-hosted web panel intended for games and apps distributed on the Meta Horizon Store. It has many features tailored specifically to the platform, such as attestation, user age-group integrations, support for achievements through Meta's Achievement API, and much more. The panel is very customizable and does not have any limits or paid tiers, unlike other backend services such as PlayFab or Epic Online Services. You can also give other people access to the web panel, such as your team, moderators, or community managers.

## 🤔 What are the features?
**multiplayered** has an ever-expanding list of options readily available when you need them, including:
- Account authentication using Meta and device attestation
  - Support for device bans
  - App and device integrity state verification
  - Package certificate verification
- Economy system with support for in-app purchases
  - Virtual currency management
    - Interval-based recharge (seconds, minutes, hours, days, weeks, months, etc.)
    - Set caps for recharging and currencies in general
      - Can be applied to currencies used as refund tokens
    - Negative numbers optionally allowed (debt)
  - Inventory system
    - Durable items (can't be consumed)
    - Consumable items (limited number of uses)
    - Limited-stock items
    - Stackability
    - Tradability
  - Rotating stores, promo-codes (virtual currency only, discounts on select items, (un-)limited uses, expiration), discounts, bundles
  - Trading items or currency
    - Virtual currencies can be made tokens for trading
      - Optional; token not needed to trade
    - Customizable cooldown and what items can be traded
  - Cases (also called drops, drop-tables, loot boxes, or containers), case keys, buy-at-once (buy multiple items at the same time)
  - Timed purchases (examples: daily spin/case/crate, log-in reward (can be automatic)), item quantities
  - Limited-time offers, honeypots, gift codes (grants a specific item(s) and/or currency, (un-)limited uses, expiration)
  - Subscriptions (real-world money and/or virtual currency, auto-renewal, customizable renewal interval)
  - Refunding purchases made with virtual currency
    - Virtual currencies can be made tokens for refunds
      - Optional; token not needed to refund
    - Customizable cooldown and what items can be refunded
- Integrations with multiplayer services like Photon
- Support for moderation tools like banning, warning, and mutes
  - Integration with voice or text chat moderation services like ToxMod and VoicePatrol
- Player statistics tracking for leaderboards and more
- Custom events and scripts with responses
- Friend system for keeping players connected
- User age-group integration for parent-managed accounts
- Managing events for engagement and prizes
- Support for user-generated content
- Achievements, quests, milestones, etc.
  - Achievements can integrate with Meta's Achievement API.
  - Quests are able to "rotate" on a customizable basis (seconds, minutes, hours, days, weeks, months, etc.)
  - Milestones automatically increase their completion threshold for the next "level."
- Insights into engagement patterns to increase retention
- A/B testing for figuring out what changes players like and don't
- News/message broadcasting to keep players informed
- Alerts for unusual actions (both from players and your team)
- Audit logs to see what actions your team makes
- Fraud prevention tools to safeguard transactions
- Webhook integrations for easier monitoring
- Test environments for testing new configurations before release
- Scheduled tasks for routine operations

Additionally, multiplayered natively supports multiple languages, like:
- English
- Spanish

## ❓ Why use multiplayered?
**multiplayered** is a good alternative to expensive, unnecessary subscriptions that provide little to improve your experience as a developer for Meta Horizon. It can also be rebranded at will due to the fact that it is self-hosted. The codebase can be easily modified and you can make an issue if you need any help (changing the code, adding more features, or just using it in general.)