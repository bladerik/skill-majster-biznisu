# skill-majster-biznisu

**Skill builder podľa metodiky Majster Biznisu** — sprievodca, ktorý ťa prevedie od konkrétneho opakovaného postupu vo tvojej firme k novému, použiteľnému AI skillu.

Tento skill je praktický bonus k prednáške **Majster Biznisu 2026-06-02** od [Lukáša Gregora](https://github.com/bladerik).

## Čo robí

Skill ťa prevedie 5 krokmi:

1. **Identifikuje** opakovaný digitálny postup vo tvojej firme
2. **Zmapuje** aký kontext (pravidlá, príklady, referencie) skill potrebuje
3. **Definuje** bezpečnostné hranice — čo AI smie, čo musí pýtať schválenie, čo nesmie nikdy
4. **Vygeneruje** kompletný `SKILL.md`
5. **Uloží** ho na správne miesto v tvojom AI agentovi, aby si ho mohol hneď používať

Celý proces trvá **15–30 minút**.

## Funguje v ktorých AI agentoch

Skill je v štandardnom Anthropic Agent Skills formáte. Funguje vo všetkých agentoch, ktoré ho podporujú:

- Codex
- Claude Code
- Cursor
- OpenCode
- Windsurf
- Antigravity
- Junie (JetBrains)
- Gemini CLI
- AWS Kiro
- Block Goose
- a ďalšie

**Pozn:** v ChatGPT bez Custom GPT s file access alebo v Claude.ai bez harness skill nedokáže súbor uložiť. Spusti ho v jednom z podporovaných agentov.

## Inštalácia (najjednoduchšie)

Otvor si Codex, Claude Code alebo iný AI agent a povedz mu:

```
Nainštaluj mi skill z bladerik/skill-majster-biznisu a spusti ho.
```

Agent sa pozrie na toto GitHub repo, stiahne SKILL.md, uloží ho do svojho skill priečinka a spustí.

To je všetko.

## Inštalácia (cez CLI, pre pokročilých)

### Codex

```bash
npx -y skills add bladerik/skill-majster-biznisu --agent codex -g -y --copy
```

### Claude Code

```bash
npx -y skills add bladerik/skill-majster-biznisu --agent claude -g -y --copy
```

### Manuálne

Skopíruj obsah [SKILL.md](./SKILL.md) do svojho lokálneho skill priečinka:

- Codex: `~/.codex/skills/majster-biznisu-skill-builder/SKILL.md`
- Claude Code: `~/.claude/skills/majster-biznisu-skill-builder/SKILL.md`
- Cursor: `~/.cursor/skills/majster-biznisu-skill-builder/SKILL.md`
- iné: pozri dokumentáciu tvojho agenta

## Po inštalácii

V tvojom AI agentovi napíš:

```
Použi skill majster-biznisu-skill-builder.
```

A skill ťa prevedie cez 5 krokov.

## Tri tézy, na ktorých skill stojí

1. **Context is King** — kvalita AI výstupu sa rovná kvalite kontextu, nie sile modelu.
2. **Pattern Replication** — kvalita skillu sa rovná kvalite pochopenia postupu, ktorý replikuje.
3. **Internal beats Commercial** — interný skill postavíš za dni. Komerčný produkt trvá mesiace. Nečakaj na "AI pre tvoj sektor". Stav si vlastný.

## Pre koho je tento skill

Pre podnikateľov, ktorí:
- prešli prednáškou Majster Biznisu (alebo vidia jej záznam)
- majú v hlave alebo v SOP-čkach jasný opakovaný postup
- chcú postaviť AI skill rýchlo, bez zložitého technického setupu

Funguje rovnako dobre, či staviaš svoj prvý skill, alebo už desiaty.

## Licencia

MIT — voľne použiteľné, môžeš si to upravovať, šíriť, použiť pre obchodné aj osobné účely.

## Spojenie

Lukáš Gregor — [bladerik](https://github.com/bladerik) na GitHube.
