## Hi, I'm Paahul

I'm a product manager working on enterprise SaaS, currently focused on identity, security, and platform problems in the iPaaS space. I've been building AI products end to end, not because I'm switching to engineering, but because the fastest way to make good calls about AI products is to have actually shipped them: structured-output prompt design, evals, background pipelines, multi-user data isolation, and the parts of the stack that don't show up in a demo.

The repos below are where I do that. Each one was a deliberate step up in architectural complexity from the last.

### What I've built

**[cadence](https://github.com/paahul/cadence)** — A personal speaking coach. Tap to record, and it transcribes, scores six dimensions of spoken communication, and emails a short read every weekday with one specific thing to work on. The product premise is calibrated honesty: per-dimension confidence labels, N/A as a feature instead of a smoothed average, and zero invented quotes (enforced in the prompt and validated server-side). Audio capture, signed-URL upload, a background analysis queue, and multi-user RLS underneath. *Next.js, Supabase, Whisper, Claude, Inngest.*

**[tripsmith](https://github.com/paahul/tripsmith)** — A travel planner that asks once how you travel, then tailors every plan to that profile. Claude returns a typed JSON schema, not prose, so the UI renders each piece as its own component. The part I care about most is the eval harness: an LLM-as-judge setup using a stronger model to score a cheaper generator, with a deliberate impossible-request fixture the model has to refuse rather than hallucinate. *Next.js, Claude, Supabase, tsx eval suite.*

**[True-Mirror](https://github.com/paahul/True-Mirror)** — AI analysis of your Apple Health data with no App Store, no Xcode, and no 2GB XML export. An iOS Shortcut reads HealthKit directly and POSTs to a backend that returns a direct read in about ten seconds. This one started from a positioning question rather than a tech one: every existing approach has a specific catch, and the clean version lives at an intersection most people don't sit at. *Next.js, Supabase, Claude, iOS Shortcuts.*

### How I think about it

There's a thread across these: AI tools that tell you the truth instead of smoothing it over. The interesting work was rarely the model call. It was the data pipeline, the eval that catches drift, the schema that keeps the model honest, and the distribution path that gets a real person to the product in under a minute.

If you're hiring for a PM who can hold a credible conversation with engineering about how AI products actually get built, that's what these are meant to show.

### Reach me

- LinkedIn: *(https://www.linkedin.com/in/paahul/)*
- Email: *sikandpaahul@gmail.com*
