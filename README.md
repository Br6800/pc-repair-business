# pc-repair-business
What actually makes sense for this type of business:

A local repair shop lives and dies on Google search — someone's laptop breaks, they Google "computer repair near me" and call the first result. That means your priority should be:


Google Business Profile — free, and arguably more important than your website for local trade. Gets you on Maps, shows your hours, collects reviews.
A simple static site on GitHub Pages (like what I've built you) — free hosting, you own it completely, loads fast.
Stripe Payment Links for taking deposits or upfront payment — free to set up, you just pay the ~1.7% + 30c per transaction fee when someone actually pays you.


Here's the rebuilt page — this time designed specifically for a local Australian repair business. The key changes from the previous version:


What's different and why:


Phone number is prominent everywhere — top bar, nav, hero, and contact section. Local service customers call first, browse second.


- Local suburb callouts — hero badge, trust strip, and reviewer locations all reference your area. This reinforces local relevance to both visitors and Google.
- Google Business Profile integration — there's a dedicated Google reviews block with a direct link to your profile. This is your most important marketing asset and the page actively drives people to it.
- Stripe payment card built into the contact section — three clickable options (Basic/Standard/Pro) that go straight to separate Stripe payment links, so booking and paying happens in one step.
- "How It Works" section — explains the drop-off/call/collect flow, which is what local repair customers actually want to know.
- Local Business schema in the <head> — invisible to visitors but tells Google exactly where you are, your hours, and what you do. Helps with Maps ranking.
- SEO title and meta description — pre-written with [suburb] placeholders so you rank for "computer repair near me" style searches.


To go live, replace all the placeholders:
YOUR-PHONE, YOUR-EMAIL, YOUR_STRIPE_*_LINK, YOUR_GOOGLE_BUSINESS_LINK, and all the [Your Suburb] / [City] tags.
