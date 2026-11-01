THE PROPOSAL GENERATOR — free giveaway from "Build It With AI" (Episode 18)

The quote you priced, grown into the document a client signs: scope by section, options the
client can accept, a payment schedule that always adds up, and terms that contain not one
sentence the machine invented — every paragraph comes from your own library file, and the page
proves that on every run.

WHAT'S IN THIS FOLDER
- Proposal_Generator.html .. THE TOOL: the finished, tested version from the end of the episode.
                             One file. Open it in any browser. No internet, no account,
                             nothing you paste leaves your machine.
- sample/items.csv ......... the episode's sample job (Juniper & Stone Landscaping — fictional)
- sample/library.csv ....... the episode's sample proposal library
- PROMPTS.txt .............. the exact three prompts from the episode, word for word
- checker.py ............... the independent second implementation (Python) used to verify the
                             tool — run: python3 checker.py items.csv library.csv
- engine_v1.js ............. FIRST DRAFT, NOT THE TOOL: the first build, kept verbatim for
                             learning, bugs and all (it writes its own
                             warranty and prices options nobody accepted)
- engine_v2.js ............. SECOND DRAFT, NOT THE TOOL: the second build, kept verbatim for
                             learning (the capital-Y option in the base
                             price, the duplicate row priced twice, the one-cent schedule)

HOW TO USE IT ON YOUR OWN JOBS
1. Open Proposal_Generator.html. Click "Load the sample job" to see it work.
2. Make your items CSV with columns: Line, Section, Item, Qty, Unit, Unit Price, Optional.
   Mark client-choice upgrades with "yes" in Optional; leave it blank otherwise.
3. Make your library CSV with columns: Kind, Fieldname, Text. Fields you need: business, client,
   project, date (YYYY-MM-DD). Then one clause row per paragraph you actually stand behind —
   your warranty, your payment terms, your exclusions. Clauses may use {{client}}, {{business}},
   {{project}}, {{contact}}, {{valid_until}}, or any field you add.
4. Pick the payment split and the validity window, tick the options your client accepts, and
   download the finished proposal as a file you can print or send.

WHY THE LIBRARY MATTERS
A proposal is a signing document. This tool assembles yours from language you wrote and numbers
it can prove; it refuses to invent. If a clause names a field the library doesn't fill, the
whole document is withheld and the page tells you which clause — a hole in a contract is worse
than no contract.

HONEST LIMITS
- It builds the document; it does not price the job. Your quantities and unit prices are yours.
  (Episode 16's Quote Re-Pricer is the other half of that story.)
- It formats no legalese and gives no legal advice. The clauses are your words; have a lawyer
  look at them once, then reuse them forever.
- The sample business is fictional. Any resemblance is coincidence.

Found a bug? Ask the AI to fix it — and make it show you the fix the way the episode does:
prove it on the numbers, not with reassurance.
