---
type: Document
title: Refund policy
description: Scaffold for this organization's refund policy — open questions until the owner fills them in.
status: draft
ksor:
  audience: [public]
---

## Open questions

This document is a placeholder. It was scaffolded on request but carries no
real policy yet — nothing here should be treated as authoritative until the
owner answers these and the document is reviewed:

- What is eligible for a refund (product, service, subscription tier)?
- What is the refund window (how many days from purchase/delivery)?
- Are there conditions (unused, original packaging, proof of purchase)?
- Is it a full refund, partial, or store credit?
- Who approves exceptions, and how does a customer request one?
- Is there a source document (a policy PDF, a legal doc, an existing page)
  this should cite?

## How to fill this in

Run the `add-sources` skill (`.agents/skills/add-sources/`) with the actual
policy — a document to convert, or dictate the terms in an interview — and it
will replace this scaffold with governed content: `sources` entries, an
`ksor.owner`, and a path to `status: stable` once approved.
