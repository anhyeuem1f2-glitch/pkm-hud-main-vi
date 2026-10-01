# pkm-hud-main-vi

Vietnamese/English-safe HUD build for the Pokémon SillyTavern card.

Current VI build: **2.10.32**

Changes in this build:
- Pokédex UI is rendered directly in Vietnamese; region/species names use official English names where appropriate.
- Badge box UI is rendered directly in Vietnamese; region/city/badge proper names use official English names.
- Map UI is rendered directly in Vietnamese instead of relying only on a DOM translation overlay.
- English map locations are aliased back to the original Chinese coordinate keys so `Pallet Town`, `Viridian City`, `Route 1`, etc. still resolve to the original map coordinates.
- Keeps original Chinese runtime keys/data attributes for compatibility with the card/MVU logic.
- Expanded deep modal/button translation coverage without translating internal schema/event keys.
