# Derek Wen｜德里克文 — English authority page (GitHub Pages draft)

Static English canonical page for entity disambiguation and GEO (Generative Engine Optimization).

**Status:** local draft only. This folder is ready to become a Pages root.  
**Do not** auto-create a GitHub repo, push, or change live sites unless Derek explicitly asks.

Canonical facts (locked 2026-10-27):
- EN name: **Derek Wen**
- ZH brand: **德里克文**
- EN one-liner: Chinese AIGC creator focused on copyable AI image/video workflows—prompts you can paste, anti-AI-slop writing, and practical playbooks.

## What’s in this folder

| File | Role |
| --- | --- |
| `index.html` | Public page (About, Links, Featured works placeholders, FAQ). Embeds Person JSON-LD. |
| `llms.txt` | Guidance for AI crawlers / citation preference |
| `person.jsonld` | Same Person schema as a standalone file |
| `NOTES.md` | URL checklist Derek must fill before “done” |
| `README.md` | This publish guide |

No frameworks, no analytics, no tracking scripts.

## Suggested repository names

Pick one:
- `derek-wen` (clearest EN canonical)
- `derekwen-aigc` (topic-disambiguating)

Avoid names that look like the Zhihu slug alone (`devin-gau`) as the repo title.

## Publish options (you do this; bot does not push)

### A. Project Pages (recommended for first ship)

1. Create an empty public repo (e.g. `derek-wen`) under your GitHub user or org.
2. Copy **all files in this directory** to the repo root (or into `docs/` if you prefer docs-folder publishing).
3. Replace every `REPLACE_ME_*` string (see `NOTES.md`).
4. Settings → Pages → Source: Deploy from a branch → `main` / root (or `/docs`).
5. Site URL will look like:  
   `https://<github-username>.github.io/derek-wen/`
6. Update `link rel="canonical"`, Open Graph URL, JSON-LD `url`, and `llms.txt` `https://derekwalldevin-wen.github.io/derek-wen/` to that final URL.
7. Optional: add a custom domain later; keep one stable canonical forever.

### B. User site (`username.github.io`)

1. Repo must be named `<github-username>.github.io`.
2. Put these files at the repo root.
3. URL: `https://<github-username>.github.io/`  
   Only use this if that domain is free for Derek’s brand and not already used for something else.

### C. Org / project under an existing brand org

Same as Project Pages; still replace canonical URL placeholders.

## Pre-flight checklist

- [ ] Featured works: 3–5 real URLs (omit empty 5th card if no skills repo)
- [ ] Canonical URL written into `index.html`, `person.jsonld`, `llms.txt`
- [ ] Spot-check FAQ against live Zhihu/X (no invented rankings)
- [ ] Bio on X still shows `Derek Wen｜德里克文` and matches EN one-liner intent
- [ ] No “全网50W” hard claim; reach note stays approximate + dated if kept

## Local preview

```bash
cd authority-site-draft
python3 -m http.server 8080
# open http://127.0.0.1:8080/
```

## Related GEO docs (workspace)

- `../canonical-identity.md`
- `../structured-assets-checklist.md`
- `../prompt-map-v1-skeleton.md`
- `../reputation-baseline-2026-10-27.md`
- `../geo-playbook-how-to-2026-10-27.md`

## Boundary

This draft is content + structure only. Deploying, DNS, GEOInflow, paid tools, and auto-posting are out of scope until Derek approves each action.
