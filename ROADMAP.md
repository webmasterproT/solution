# Roadmap

## Where We Are

🟡 **Pre-alpha** — Specs written, looking for builders.

---

## Phase 0: Foundation (Weeks 1-4)

**Goal:** Prove the pieces work together.

- [ ] Mesh installer running on 3+ test devices
- [ ] Yggdrasil nodes can ping each other
- [ ] Basic app shell (React Native)
- [ ] NFC read/write working
- [ ] Ed25519 keypair generation in app
- [ ] Basic HER structure defined

**Deliverable:** Devices on mesh, app can read NFC, keys work.

---

## Phase 1: Vouch (Weeks 5-8)

**Goal:** Create tokens.

- [ ] Vouch flow in app
- [ ] Proximity verification (mesh ping + GPS fallback)
- [ ] HER creation and local storage
- [ ] HER broadcast to mesh
- [ ] Basic IPFS pinning
- [ ] Capsule generation (QR code)

**Deliverable:** Can create new token holders via vouch process.

---

## Phase 2: Safety (Weeks 9-12)

**Goal:** Alert system works.

- [ ] Alert trigger (button + NFC tap)
- [ ] Alert broadcast via mesh
- [ ] Responder notification
- [ ] Accept/respond flow
- [ ] Resolution logging
- [ ] Basic responder signup

**Deliverable:** Press button, nearby holders get alert, someone responds in 60 seconds.

---

## Phase 3: Epochs & Anchoring (Weeks 13-16)

**Goal:** History is permanent.

- [ ] Epoch builder (collect objects, build MMR)
- [ ] Witness signing (start with 3-5 trusted nodes)
- [ ] Bitcoin anchor (testnet first)
- [ ] Merkle proof generation
- [ ] Capsule verification (offline)

**Deliverable:** Weekly epochs anchored to Bitcoin testnet, verifiable capsules.

---

## Phase 4: Voting (Weeks 17-20)

**Goal:** Decisions happen.

- [ ] Proposal creation
- [ ] Proximity weight calculation
- [ ] Vote casting and aggregation
- [ ] Result publication
- [ ] Result anchoring

**Deliverable:** Can propose, vote, and see results with proximity weighting.

---

## Phase 5: Meetings & Empathy (Weeks 21-24)

**Goal:** Full system.

- [ ] Meeting request/notification
- [ ] Check-in via NFC
- [ ] Meeting logging
- [ ] Empathy invitation flow
- [ ] Scheduling and coordination
- [ ] Reflection/debrief tools

**Deliverable:** Full cycle: vouch → vote → meeting → empathy → resolution.

---

## Phase 6: Pilot (Weeks 25+)

**Goal:** Real people, real problems.

- [ ] 100 token holders in one community
- [ ] Real issues proposed and voted
- [ ] Real safety alerts
- [ ] Real meetings
- [ ] Iterate based on feedback

**Deliverable:** Working system in production with real users.

---

## What Success Looks Like

**6 months:** 100 people in one suburb using the system daily.

**12 months:** Multiple communities. Cross-community vouching. Safety response proven.

**24 months:** Can't be ignored. Politicians start asking questions. We don't need them.

**5 years:** The old system starts to look as absurd as it is.

---

## How to Help

See [CONTRIBUTING.md](CONTRIBUTING.md).

We need:
- App developers (React Native)
- Mesh networking experience
- Cryptography (BLS, Merkle proofs)
- Community organizers
- Pilot community (~100 people)

---

## The Point

This isn't a startup with a roadmap to acquisition.

This is infrastructure for human coordination.

The timeline matters less than the direction.

We're building the ants' coordination mechanism.

3 seconds. One decision. Done.

---

```
∧,,,∧
(  ̳• · • ̳)
/    づ♡
```
