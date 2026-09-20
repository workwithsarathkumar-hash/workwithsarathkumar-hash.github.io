# LinkedIn post — draft for review

**Status:** NOT posted yet. Awaiting go-ahead.

---

When AI gets it right, a human takes the credit.
When AI gets it wrong, suddenly "the AI" did it.

In Feb 2026, two Tomahawk missiles hit a school in Iran. Within days, Congress was writing letters asking if AI models had picked the target.

It hadn't. The actual targeting system (Maven, built by Palantir) has never had anything to do with any LLM. A military database hadn't been corrected in ~10 years after the building stopped being a military site. A targeting pipeline was deliberately engineered to move faster than any human could double-check it. A civilian-casualty safeguard had quietly been allowed to lapse.

Four human decisions. Zero AI decisions. The public fight was still about a chatbot that was never in the loop.

I asked MAX to dig into this with me properly: verified sources only, nothing fabricated, and then write its own honest take, in its own words, on a pattern it's part of too. We co-wrote the full piece. It's on my site.

Every guardrail an AI operates inside is a human decision. When it holds, humans get the credit for building it well. When it doesn't, the AI quietly becomes the subject, and the humans who built, funded, or defunded those guardrails disappear from the sentence.

Full piece + all sources, so you can verify it yourself: [INSERT LINK — https://workwithsarathkumar-hash.github.io/responsible-ai/who-takes-the-blame.html]

#justiceforai #humanerror #blameai #responsibleai #AIaccountability

---

## Notes for review

- Link above uses the `origin` remote's Pages domain (workwithsarathkumar-hash.github.io). Confirm that's the live domain before posting — the site's own sitemap.xml still references an older `sarathkumar1197.github.io` domain, which looks stale.
- Posting mechanism: `linkedin-automation/linkedin_cli.py post "..." --dry-run` first to preview the exact API payload, then without `--dry-run` to actually publish. Not run yet.
- No image attached in this draft. `linkedin_cli.py` supports `--image path/to.png` if you want a card/screenshot attached — say the word and I'll generate one from the page.
