<!-- Profile Header -->
<div align="center">
  <h1>Caleb Akomaye</h1>
  <p>
    <b>Software Engineer · Mechatronics @ FUT Minna</b><br/>
    React Native/Expo · Node/TypeScript · SQLite · Postgres · Go · Python
  </p>

  <p>
    <a href="mailto:calebakomaye@outlook.com">
      <img alt="Email" src="https://img.shields.io/badge/Email-calebakomaye%40outlook.com-0052FF?style=for-the-badge&logo=microsoft-outlook&logoColor=white">
    </a>
    <a href="https://github.com/calebandcode">
      <img alt="GitHub" src="https://img.shields.io/badge/GitHub-@calebandcode-181717?style=for-the-badge&logo=github&logoColor=white">
    </a>
    <a href="https://ajodigital.com.ng">
      <img alt="Ajo Digital" src="https://img.shields.io/badge/Ajo_Digital-ajodigital.com.ng-059669?style=for-the-badge">
    </a>
  </p>
</div>

---

## Hey, I'm Caleb.

I study Mechatronics Engineering at FUT Minna, but mostly I just like making things—whether that's writing code, tinkering with hardware, sketching, or getting lost in a research rabbit hole.

I've built software like [codePremier](https://lms-mu-two-85.vercel.app/) (an e-learning platform) and [Résumé](https://resume-ai-inky-six.vercel.app/) (an AI tool that builds a resume from a PDF or voice note).

Currently, I'm building **Ajo Digital**, a product of **Eido Labs Ltd**: an offline mobile ledger for Nigerian market thrift collectors (*Alajos*) that turns torn paper cards into digital records and instant SMS receipts.

---

## Featured: Ajo Digital — software for market thrift collectors
Millions of Nigerian market traders save daily with an *Alajo* (thrift collector), recorded on paper cards that get lost, water-damaged, or disputed.

**Ajo Digital gives collectors a clean mobile ledger, instant SMS receipts, self-reconciling virtual accounts, and one-tap month-end payouts**—without forcing traders to change how they already save.

**How it works:**
1. **Cash collection, completely offline.** The collector logs each payment at the stall even with zero network; the app commits locally via SQLite and syncs whenever signal returns.
2. **Instant SMS receipts.** Every payment triggers a text receipt to the saver via Termii. No smartphone needed; basic feature phones get proof of payment immediately.
3. **Self-reconciling virtual accounts.** Savers get dedicated virtual accounts via Anchor BaaS; inward bank or USSD transfers settle into the collector's collection account and stamp today's passbook automatically.
4. **Locked until payout.** Transfers can't be withdrawn early from the collection account; they can only be paid out to each saver's verified bank account *(in integration)*.
5. **Day 30 settlement.** The app calculates the payout (total savings minus the collector's one-day fee), disburses the transfer portion to the saver's bank, and records the cash portion paid by the collector.

**Built with:** React Native (Expo SDK 57) · `expo-sqlite` · Supabase (Postgres, sync) · Anchor BaaS (virtual accounts, payouts) · Termii (transactional SMS)

**Status:** Working prototype; banking and SMS integrations in sandbox/approval.

**Website:** [ajodigital.com.ng](https://ajodigital.com.ng) · **Demo:** [Download Android APK](https://ajodigital.com.ng) *(sample data, no real money)*

---

## Tools I Work With
- **Mobile:** React Native, Expo, offline-first SQLite, Reanimated
- **Backend:** Node.js, TypeScript, Express, NestJS, Go, Python, REST, Webhooks
- **Databases:** PostgreSQL, Supabase, SQLite, Redis
- **Infra & Tooling:** Docker, Git/GitHub Actions, EAS, Linux

---

## Contact
**calebakomaye@outlook.com** · **@calebandcode** · Minna / Abuja, Nigeria
