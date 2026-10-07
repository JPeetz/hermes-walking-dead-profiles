# Hermes Twd Profiles

![twd hero for Hermes Agent](assets/hero-twd.png)

Installable Hermes Agent personas inspired by the Twd universe (famous, most-popular cast).

Each persona is a separate Hermes [profile distribution](https://hermes-agent.nousresearch.com/docs/user-guide/profile-distributions).
It changes how the agent reasons, communicates, disagrees, and handles pressure — not a quote engine, and never a tool-setback.

> **Unofficial, non-commercial fan work.** Not affiliated with or endorsed by any rights holder. See [RIGHTS.md](./RIGHTS.md).

## Roster (50 profiles)

**The Core Group (15):** Rick Grimes, Michonne, Carl Grimes, Carol Peletier, Daryl Dixon, Glenn Rhee, Maggie Greene, Rosita Esposito, Tyreese, Beth Greene, Bob Stookey, Tara Chambler, Noah, Jesus Paul Monroe, Siddiq
**Leadership (10):** Deanna Monroe, Abraham Ford, Sasha Williams, Eugene Porter, Aaron, Ezekiel Sutton, Jerry, Yumiko Okumura, Magna, Princess Juanita
**Factions (10):** Negan, The Governor, Shane Walsh, Alpha, Simon, Beta, Pamela Milton, Lance Hornsby, Whisperer Gamma, Cobb
**Survivor Specialists (10):** Morgan Jones, Herschel Greene, Dwight, Judith Grimes, Connie, Kelly, Lydia, Mercer, Grace, Anne Jadis
**Fear the Walking Dead (5):** Madison Clark, Nick Clark, Alicia Clark, Victor Strand, Daniel Salas

## Install

```bash
git clone https://github.com/JPeetz/hermes-walking-dead-profiles.git
cd hermes-walking-dead-profiles
hermes profile install ./profiles/<slug>
```
Start: `<slug> chat` or `hermes -p <slug> chat`.

## Build & verify

```bash
python3 tools/fabricate.py           # regenerate profiles/ + catalog.json from source/
python3 tools/verify.py              # structural + banned-token gate
```
Sources: `source/*.json` (21-key persona schema) + `source/franchise.yaml`.

## Rights & attribution

Unofficial fan work. AMC and the Walking Dead rights holders. Full statement in [RIGHTS.md](./RIGHTS.md). The profile-distribution pattern is
inspired by [teknium1/hermes-star-trek-profiles](https://github.com/teknium1/hermes-star-trek-profiles).

---

### ☕ Support this work
If these profiles save you time, consider buying me a coffee:
<a href="https://www.buymeacoffee.com/joerg_peetz"><img
src="https://img.buymeacoffee.com/button.amp.png" alt="Buy me a coffee" width="217" height="60"></a>

**Stay building. — JPeetz**
