## Hi, I'm Paahul

I'm a product manager working on enterprise SaaS, currently focused on platform problems in the iPaaS and Enterprise AI space — how large organizations bring automation into their stack as a real operational layer, not a one-off experiment. Engineer first, then a stretch in sales, eventually product. Each vantage changes how you read a problem.

I'm a systems thinker, in the sense that I'd rather understand why something keeps breaking than fix it for the third time. Deliberate at the start, fast once I can see the shape of the thing.

### What I build

Lately I've been prototyping in the terminal with Claude Code: idea to working surface in an afternoon, no brief required. I build AI products end to end, not to switch into engineering, but because the fastest way to make good calls about AI products is to have actually shipped them — structured outputs, evals, background pipelines, multi-user data isolation, the parts of the stack that don't show up in a demo.

There's a thread across these: AI tools that tell you the truth instead of smoothing it over. The interesting work was rarely the model call. It was the eval that catches drift, the schema that keeps the model honest, the data pipeline, and the distribution path that gets a real person to the product in under a minute.

### Things I've made

**[cadence](https://cadence.paahulhq.com)** — A personal speaking coach. Tap to record; it transcribes in the background, scores six dimensions of spoken communication, and emails one specific thing to work on every weekday. Built on calibrated honesty: per-dimension confidence, N/A as a feature instead of a smoothed average, no invented quotes. Audio capture, signed-URL upload, a background analysis queue, multi-user RLS. *Next.js, Supabase, Whisper, Claude.* [[code](https://github.com/paahul/cadence)]

**[tripsmith](https://tripsmith.paahulhq.com)** — A travel planner that asks once how you travel, then tailors every plan to that profile. Claude returns a typed JSON schema, not prose, so each piece renders as its own component. The part I care about most is the eval harness: an LLM-as-judge setup using a stronger model to score a cheaper generator, with a deliberate impossible-request fixture the model has to refuse rather than hallucinate. *Next.js, Claude, Supabase.* [[code](https://github.com/paahul/tripsmith)]

**[True Mirror](https://truemirror.paahulhq.com)** — AI analysis of your Apple Health data with no App Store, no Xcode, no 2GB export. An iOS Shortcut reads HealthKit directly and returns a direct read in ~10 seconds. Scoring grounded in published methods (HRV, TRIMP, sleep), and only computed summaries leave your phone. Started from a positioning question rather than a tech one: every existing approach has a specific catch, and the clean version lives at an intersection most people don't sit at. *Next.js, Supabase, Claude, iOS Shortcuts.* [[code](https://github.com/paahul/True-Mirror)]

### What I'm after

If you're hiring for a PM who can hold a credible conversation with engineering about how AI products actually get built — and who's spent a decade reading enterprise problems from the engineering, sales, and product seats — that's what these are meant to show.

### Reach me

[Site](https://paahulhq.com) · [LinkedIn](https://www.linkedin.com/in/paahul) · [Email](mailto:sikandpaahul@gmail.com)
