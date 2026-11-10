ï»¿# Supreme Schemes

Crusader Kings III intrigue mod. Version 0.4.0. Supported game version 1.20.*.

Embrace the Supreme Schemer trait for days-scale plots, near-guaranteed success at High intensity, plus hostile schemes to steal artifacts and titles through intrigue (not war).

Player Supreme Sovereigns (with Supreme Sovereign loaded) can also **Demand Strong Hook** on any living character â€” auto-accept, no cooldown, grants a strong favor hook toward you.

**M4 Auto Strong Hooks:** with Auto Strong Hooks On (hub default), gaining a new direct vassal silently grants you a strong favor hook on them. **Supreme Schemes: Actions** opens the Actions hub; **Hook All Vassals** hooks every current direct vassal you can still hook (one summary toast, no cooldown).

Player Supreme Schemers and/or Supreme Sovereigns also bypass strong-hook spend cooldowns and Fabricate Hook scheme cooldowns when using hooks.

Canonical working copy: `Documents/Development/CK3 Mods/ssc`.

Soft peers: Supreme Sovereign, Exalted Reliquary, Exalted Advisor, Succession Unity (detection only; no hard dependency). Stolen Reliquary heirlooms may reclaim via never-lost â€” intended soft tension. Enable Supreme Schemes and play a Supreme Sovereign for hook features.

Custom scheme keys: `ssc_steal_artifact`, `ssc_fabricate_title_claim`, `ssc_steal_title`.
Interaction: `ssc_demand_strong_hook_interaction`.
Decision: `ssc_schemes_actions_decision` (hub event `ssc_actions.1001`, option Hook All Vassals).
On-action: `ssc_on_vassal_gained` (append on `on_vassal_gained`).
