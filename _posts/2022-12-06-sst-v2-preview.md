---
layout: blog
title: "SST V2 Preview"
author: jay
---

As the first episode of the [Is serverless ready?](https://isserverlessready.com) series, we are showing off a preview of SST's upcoming v2 release.

You can check it out on YouTube here.

<div class="youtube-container">
  <iframe src="https://www.youtube-nocookie.com/embed/qEKUNZWbj-8" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div>

The video is timestamped and here's roughly what's going to be released as a part of SST v2:

1. **Monopackage** — SST is now going to use a monopackage. Moving from `@serverless-stack` to simply `sst`.
1. **New config** — There's a new config file. A `.js` file instead of the `.json`. Similar to what Vite has.
1. **New functions API** — We've refactored the props in the SST Functions construct.
1. **Improved codegen** — We've reworked how SST codegens your types.
1. **pnpm support** — We've made SST compatible with [pnpm](https://pnpm.io). We've internally migrated to pnpm as well!
1. **New CLI UI** — There's an all new CLI UI, that makes it easier to figure out what the CLI is doing.
1. **Faster CLI** — We've refactored the entire CLI codebase and optimized for speed. It's a lot faster than before.
1. **Faster Live Lambda Dev** — We've also adopted a new debug stack infrastructure, so [Live Lambda Dev](https://docs.sst.dev/live-lambda-development) is now way faster than before!
1. **Building modern frontends** — We are also going to be introducing new constructs for [Astro](https://astro.build) and [Solid](https://www.solidjs.com).
1. **OpenNext** — We also launched a new open source initiative called [OpenNext](https://open-next.js.org) to allow Next.js apps to work on AWS, exactly like they do on Vercel.

SST v2 is now in beta and we need your help testing it. So [**make sure to join us on Discord and take it for a spin**]({{ site.discord_invite_url }}).
