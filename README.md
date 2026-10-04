# TutorCart AI

**Tagline:** Learn before you buy. Buy with confidence.

TutorCart is an AI personalized product tutor for commerce. It adapts explanations to a shopper's knowledge level, teaches the tradeoffs that matter, then recommends the right product or bundle and can hand off to cart/checkout.

## Run
Open `index.html` in any browser. No install, no API key.

## 60-second demo flow
1. Choose Beginner + Under $700.
2. Click **Start personalized tutor**.
3. Pick **Milk drinks / lattes**.
4. Pick **Balanced machine + grinder**.
5. Show the recommendation and click **Add personalized bundle to cart**.

## Production architecture
- Storefront widget
- Catalog/inventory/policy retrieval
- Shopper profile + session memory
- LLM personalization agent
- MCP/API actions for inventory, bundling, cart and checkout
- Merchant analytics dashboard

## Hackathon note
The prototype is intentionally scripted so it cannot fail during a live demo. The product architecture is designed for real model + commerce integrations.
