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
3. **It is what the Centre accepts.** Under §8 of `prd.md`, a story is done when every
   criterion has been checked and recorded as met, and the record is tagged. This file
   is that record.

Write it as you go, not afterwards. A criterion marked "not met", with the reason, is
worth more than eight ticks nobody can stand behind.

---

## Sprint 1 — story S1 (in the Week 6 lab)

### The story

As an enquirer, or the front desk acting for one, I want to submit an enquiry with
only the details the Centre needs, and get a reference, so that I can ask for help
without an email address and know it arrived.

### The prompt I gave the agent

### The assumptions the agent listed

Write down any you did not expect. Each one is a place where the PRD was silent.

### The acceptance criteria

The full criteria are in §5 of `prd.md`. Try each one. Write met or not met, and how
you checked it.

| # | Criterion (short) | Met? | How I checked |
|---|---|---|---|
| 1 | Phone or email, not neither | | |
| 2 | Only the listed fields | | |
| 3 | No NRIC, date of birth, address, income or documents | | |
| 4 | Notice above Submit, same size of text | | |
| 5 | Reference `CPBC-` and four digits, different each time | | |
| 6 | Three working days, and the phone number | | |
| 7 | Count survives a reload; nobody's details shown | | |
| 8 | Contrast at least 4.5 to 1 | Not met — not checked by me | The facilitator checked the demo build, not mine |

### What I found

Anything the agent did that nobody asked for:

Tag: `v0.1`

---

## Sprint 2 — story S2 (homework)

### The story

As the Centre Manager, I want to see every new enquiry in one list, with any
time-critical enquiry at the top, so that urgent matters reach a volunteer first.

### The prompt I gave the agent

### The assumptions the agent listed

### The acceptance criteria

The full criteria are in §5 of `prd.md`. Try each one, using the five test enquiries on
the lab page. Write met or not met, and how you checked it.

| # | Criterion (short) | Met? | How I checked |
|---|---|---|---|
| 1 | A "Centre Manager's list" link; form and list never on screen together | | |
| 2 | One row per enquiry: reference, name, date and time submitted, deadline | | |
| 3 | Deadline within 30 days marked "Time-critical", above the rest, earliest first | | |
| 4 | Deadline passed marked "Deadline passed", at the very top | | |
| 5 | All others below, newest first | | |
| 6 | "No enquiries yet." when there are none | | |
| 7 | S1's criteria 1 and 5 still pass | | |

### What I found

Anything the agent did that nobody asked for:

Tag: `v0.2`
