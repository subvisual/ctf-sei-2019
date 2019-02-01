---
permalink: /challenges/c
layout: challenge
---

# Level 5

You probably got the gist of this now, haven't you?

Now, this level is a bit different. To move forward, you just need to:

1. Grab all the answers from all previous challenges;
2. Join them together, separated by a comma, **all downcase, no spaces**;
3. Find the `keccak256` hash of that entire string (you're smart, you'll figure it
   out);
4. the URL for the next part is `{{ "/challenges/YOUR_HASH_HERE" | relative_url
   }}`.
