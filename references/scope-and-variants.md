# Scope And Variants

Use this file when the proposed skill may be too complex for a simple text-only `SKILL.md`.

## Out-of-Scope Signals

Treat the skill as advanced or experimental if it requires:

- video frame extraction, audio extraction, transcription pipeline, media processing
- deterministic scripts such as Python, JavaScript, shell, `yt-dlp`, `ffmpeg`
- external API keys such as OpenAI, Openrouter, fal.ai, ElevenLabs, CRM APIs
- database, queue, scheduling infrastructure, background workers
- OAuth or authentication setup
- installing binary dependencies
- autonomous sending, publishing, payments, deleting, or system changes

Do not silently attempt advanced setup.

## Three Build Variants

For complex skills, show this comparison:

```text
Toto je komplexnejší skill. Vieme ísť tromi cestami:

1. Lite verzia: rýchly text-only skill bez integrácií.
   Výhoda: hotové rýchlo. Nevýhoda: bude robiť len drafty a odporúčania.

2. Best-practice textový skill (odporúčam):
   zapracujem proces, kontext, časté chyby, výstupný template, checklist a validáciu.
   Výhoda: použiteľné v praxi bez technického setupu.

3. Experimentálna advanced verzia:
   počíta so skriptami, API, dátami alebo integráciami.
   Výhoda: môže ísť ďalej. Nevýhoda: môže vyžadovať programátorský setup
   a nemusí sa podariť dokončiť v tejto session.

Ktorú cestu chceš?
```

If user chooses **1**, keep it intentionally simple and transparent.

If user chooses **2**, generate a robust text-only skill and apply the quality checklist from `generated-skill-template.md`.

If user chooses **3**, set `experimental_mode = true`.

## Experimental Mode

In experimental mode, remind the user at every major step:

```text
Poznámka: stále sme v experimentálnom režime.
Tento skill môže potrebovať technický setup mimo samotného SKILL.md.
```

The generated skill must include:

```markdown
## Experimentálny režim

Tento skill je experimentálny, pretože [konkrétny dôvod].

Pred použitím over:
- [required setup 1]
- [required setup 2]
- [known limitation or risk]
```

## Safer Alternative Pattern

When the user wants something too technical, propose a useful 80 percent text-only version:

- YouTube thumbnail generator -> skill that reviews uploaded screenshots/frame descriptions and proposes hooks/compositions
- real-time transcription -> skill that processes pasted transcript and extracts decisions/tasks
- CRM auto-routing -> skill that classifies pasted lead data and recommends routing
- voice clone pipeline -> skill that drafts voiceover scripts and approval checklist

Use this phrasing:

```text
Toto už je technicky zložitejšie. Vieme ale spraviť bezpečnú textovú verziu,
ktorá vyrieši 80 percent hodnoty bez integrácií.
```
