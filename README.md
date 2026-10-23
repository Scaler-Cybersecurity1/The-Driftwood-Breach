# The-Driftwood-Breach
**Topic:** Account takeover / data exfiltration · **Time:** 25–35 min

**Scenario.** You are a Tier-2 SOC analyst at Driftwood Analytics (a SaaS company).
A customer-success manager reports a phishing email, and odd traffic follows on the
customer portal. Someone may have taken over an account and stolen data.

**Your task.** Investigate using the two tools on the right:
- **Reported email** — read the full headers, not just the body.
- **Access logs** — a searchable console of portal traffic. Use the search box and
  quick-filter chips to trace the attack through hundreds of lines of normal traffic
  and decoys.

**You must find:**
1. The domain the phishing email actually came from.
2. The portal account that was taken over.
3. The attacker's source IP address (watch out — a second outside IP is just a
   scanner and is not the attacker).
4. How many customer records were exported.
