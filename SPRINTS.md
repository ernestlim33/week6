# Sprint record

Name:

## What this file is for

This file is the record of each sprint: what you asked the agent for, what you checked,
and what you found. The stories come from the backlog in §5 of `prd.md`.

It matters for three reasons.

1. **It is how you review what you cannot read line by line.** You cannot check every
   line the agent wrote. You can check every criterion, and write down what happened.
2. **It is evidence.** "We tested it" is a claim. A record that names each criterion,
   how it was checked, and what was still not met, is evidence that someone reviewed
   the work.
3. **It is the handover.** Anyone who picks up your system later can see what was
   promised, what was checked, and what is still open.

Write it as you go, not afterwards. A criterion marked "not met", with the reason, is
worth more than eight ticks nobody can stand behind.

---

## Sprint 1 — story S1 (in the Week 5 lab)

### The story

As an enquirer, or the front desk acting for one, I want to submit an enquiry with
only the details the Centre needs, and get a reference, so that I can ask for help
without an email address and know it arrived.

### The acceptance criteria

The criteria are in §5 of `prd.md`. Try each one. Write met or not met, and how you
checked it.

| # | Criterion (short) | Met? | How I checked |
|---|---|---|---|
| 1 | Phone or email, not neither | | |
| 2 | Only the listed fields | | |
| 3 | No NRIC, date of birth, address, income or documents | | |
| 4 | Notice above Submit, same size of text | | |
| 5 | Reference `CPBC-` and four digits, different each time | | |
| 6 | Three working days, and the phone number | | |
| 7 | Count survives a reload; nobody's details shown | | |
| 8 | Contrast at least 4.5 to 1 | | |

### The prompt I gave the agent

### The assumptions the agent listed

Write down any you did not expect. Each one is a place where the PRD was silent.

### What I found

Anything the agent did that nobody asked for:

Tag: `v0.1`

---

## Sprint 2 — story S2 (homework)

### The story

As the Centre Manager, I want to see every new enquiry in one list, with any
time-critical enquiry at the top, so that urgent matters reach a volunteer first.

### The acceptance criteria

Write at least four. Use S1's criteria as the model. Each one must be checkable by
someone who was not in the room.

S2 says "time-critical" but does not say what it means. One of your criteria must
decide it.

| # | Criterion | Met? | How I checked |
|---|---|---|---|
| 1 | | | |
| 2 | | | |
| 3 | | | |
| 4 | | | |

### The prompt I gave the agent

### What I found

Anything the agent did that nobody asked for:

Does S1 still work? (Try S1's criteria 1 and 5 again.)

### What I changed in `prd.md`

- §5:
- §6:

Tag: `v0.2`

---

## Licence

I chose ... because ...
