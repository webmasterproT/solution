# Token

**One token per human. Community safety in 60 seconds. Proximity-weighted democracy. $9 to join.**

---

## What Is This?

A system to replace broken governance with something that works.

- **The Token** — One per human, verified by 3 others in person, anchored to Bitcoin
- **The Ring** — $9 NFC ring, tap to vote/alert/identify
- **The Safety Button** — 60-second community response, not 20-minute police response
- **Proximity Voting** — Your vote weighs more the closer you are to the issue
- **Empathy Invitations** — Can't agree? Swap lives for a week. Then decide.

No politicians. No corporations. No central server. Can't be shut down.

---

## Why?

| Current System | This System |
|----------------|-------------|
| $400/day per prisoner | Community-based resolution |
| 45% recidivism | People facing consequences of their choices |
| 20+ min police response | 60 second community response |
| Politicians decide everything | Affected people decide |
| $32B/year on justice | Costs almost nothing |

Australia has $19 trillion in wealth and 1 in 6 kids in poverty. The math doesn't fail. The system does.

---

## Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                     LAYER 1: BITCOIN ANCHOR                      │
│         Permanent. Immutable. "This happened."                   │
└─────────────────────────────────────────────────────────────────┘
                              ▲
┌─────────────────────────────────────────────────────────────────┐
│                 LAYER 2: HUMAN EXISTENCE RECORD                  │
│         Identity. One per human. Stored on IPFS.                 │
└─────────────────────────────────────────────────────────────────┘
                              ▲
┌─────────────────────────────────────────────────────────────────┐
│                     LAYER 3: MESH NETWORK                        │
│         Yggdrasil + BATMAN-adv. Works offline.                   │
└─────────────────────────────────────────────────────────────────┘
                              ▲
┌─────────────────────────────────────────────────────────────────┐
│                        PHYSICAL: NFC RING                        │
│         $9. No battery. Tap to do everything.                    │
└─────────────────────────────────────────────────────────────────┘
```

---

## How It Works

1. **Get token** — Find 3 holders, meet in person, they vouch, you're in (5 min)
2. **Have problem?** — Initiate a meeting
3. **Affected people show up** — Proximity-weighted
4. **Can't agree?** — Empathy invitation (swap lives for a week)
5. **Decide together** — People who live with consequences make the call
6. **Iterate** — Until roughly equal and okay

---

## Docs

| Document | Description |
|----------|-------------|
| [MANIFESTO.md](MANIFESTO.md) | The full reasoning and vision |
| [TECHNICAL-SPEC.md](TECHNICAL-SPEC.md) | Architecture, schemas, build plan |
| [JUSTIFICATIONS.md](JUSTIFICATIONS.md) | "What about..." — objections answered |
| [ROADMAP.md](ROADMAP.md) | Phases and milestones |

---

## Tech Stack

- **Anchor:** Bitcoin (OP_RETURN, 40 bytes/epoch)
- **Identity:** Ed25519 signatures, BLS12-381 for witnesses
- **Storage:** IPFS, Arweave
- **Mesh:** Yggdrasil, BATMAN-adv, Nebula
- **App:** React Native (iOS/Android)
- **Ring:** Off-shelf NFC, ~$2-4 wholesale

---

## Status

🟡 **Pre-alpha** — Specs written, looking for builders

### Need

- [ ] App developers (React Native)
- [ ] Mesh networking experience
- [ ] Cryptography (BLS, Merkle proofs)
- [ ] Community organizers
- [ ] Pilot community (~100 people)

---

## Quick Start (Coming Soon)

```bash
# Not yet — help us build it
git clone https://github.com/webmasterproT/solution.git
cd solution
# TODO: everything
```

---

## FAQ

**"This is utopian nonsense."**

Every component exists today. Bitcoin (15 years). Mesh networking (decades). NFC (everywhere). IPFS (running now). The innovation is the combination.

**"What about serial killers?"**

The current system had Bradley Edwards and released him. Then he killed three women. Our system: victim involvement from day one, community visibility, contained community (not cage) for true predators.

**"What about privacy?"**

You already have none — corporations track everything. This is mutual visibility. You see me, I see you. Equal.

**"People are too selfish."**

Systems shape behavior. Current system rewards hoarding. This one rewards connection. Same humans, different outcomes.

See [JUSTIFICATIONS.md](JUSTIFICATIONS.md) for more.

---

## Contributing

We need help. If you can code, organize, write, or just want to be part of the pilot — open an issue or reach out.

This is public domain. Fork it. Build it. Improve it.

---

## License

**Public Domain (CC0)**

No rights reserved. Build it. Don't let it die.

---

## Author

Criminologist, Australia. Health issues, can't speak most of the time. Ideas shouldn't die with people.

If something happens to me: build it anyway.

---

```
∧,,,∧
(  ̳• · • ̳)
/    づ♡
```
