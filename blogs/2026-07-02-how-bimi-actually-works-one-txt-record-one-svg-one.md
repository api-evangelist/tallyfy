---
title: "How BIMI actually works: one TXT record, one SVG, one certificate"
url: "https://tallyfy.com/engineering-how-bimi-works/"
date: "2026-07-02"
feed_url: "https://tallyfy.com/blog/feed/"
---
Every BIMI logo you see in Gmail resolves from a single DNS TXT record pointing at an SVG file and an X.509 certificate. We run the whole stack in production for tallyfy.com. This teardown walks the exact lookup mailbox providers perform, dissects our live DigiCert certificate down to OID level, and explains why our 771-byte logo took three attempts.
