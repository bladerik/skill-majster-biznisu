# Guided Questions

Use this file when interviewing the user. Ask **one question at a time**. Most questions should give 3-5 realistic options plus `Vlastná odpoveď`.

## Pattern

```text
[One clear question]

Vyber jednu možnosť, alebo napíš vlastnú:

1. [Recommended option] (odporúčam)
2. [Useful alternative]
3. [Useful alternative]
4. [Useful alternative, if useful]
5. Vlastná odpoveď
```

Avoid yes/no when a concrete menu helps the user think.

## Follow-up After Broad Category

```text
Čo konkrétne má skill robiť?

Vyber jednu možnosť, alebo napíš vlastnú:

1. Z dopytu pripraviť cenovú ponuku alebo kalkuláciu
2. Z dopytu pripraviť odpoveď klientovi alebo follow-up po obhliadke / hovore
3. Z poznámok, hovoru alebo dokumentu vytiahnuť dôležité body a ďalšie kroky
4. Z témy pripraviť draft obsahu v mojom štýle
5. Opakovať interný postup tímu: pripomienky, edukácia, šablóny, reporting
6. Vlastná odpoveď
```

## Process Questions

### Trigger

```text
Čo spúšťa tento postup?

Vyber jednu možnosť, alebo napíš vlastnú:

1. Príde dopyt alebo správa od klienta, email, formulár, telefón
2. Mám poznámky, prepis hovoru, obhliadky alebo dokument
3. Potrebujem pripraviť cenovú ponuku alebo kalkuláciu
4. Potrebujem pripraviť obsah, post alebo email do publika
5. Nastane opakovaná interná situácia v tíme, pripomienka, šablóna, report
6. Vlastná odpoveď
```

### Current Steps

```text
Ako dnes postup vyzerá?

Vyber najbližšiu možnosť, alebo napíš vlastnú:

1. Prečítam vstup, vyberiem dôležité info, pripravím odpoveď, skontrolujem a odošlem
2. Prejdem dopyt, zistím rozsah, urobím kalkuláciu, pošlem ponuku
3. Prejdem poznámky, vytiahnem body, určím úlohy, pošlem zhrnutie
4. Zoberiem tému, navrhnem angle, napíšem draft, upravím tón
5. Skontrolujem kritériá, zaradím prípad, odporučím ďalší krok
6. Vlastná odpoveď
```

If the user chooses an option, ask one clarifying follow-up only if needed:

```text
Ktorý krok je najdôležitejší, aby AI nepokazila?

1. Výber dôležitých údajov zo vstupu
2. Správny výpočet / klasifikácia / rozhodnutie
3. Tón a forma výstupu
4. Kontrola pred odovzdaním
5. Vlastná odpoveď
```

### Output

```text
Aký výstup má skill pripraviť?

Vyber jednu možnosť, alebo napíš vlastnú:

1. Draft emailu / odpovede / ponuky pripravený na kontrolu
2. Štruktúrované zhrnutie s ďalšími krokmi
3. Content draft alebo viac variantov textu
4. Rozhodnutie s krátkym odôvodnením
5. Checklist alebo report
6. Vlastná odpoveď
```

### Human Decision Point

```text
Kde musí rozhodnúť človek?

Vyber jednu možnosť, alebo napíš vlastnú:

1. Pred odoslaním alebo publikovaním výstupu (odporúčam)
2. Pri cene, zľave alebo obchodných podmienkach
3. Pri citlivých údajoch alebo VIP klientoch
4. Pri nejasnom alebo rizikovom prípade
5. Vlastná odpoveď
```

## Context Questions

### Rules

```text
Aké pravidlá musí skill dodržiavať?

Vyber najbližšiu možnosť, alebo napíš vlastné pravidlá:

1. Stručne, jasne, bez hype a bez generického AI tónu
2. Drž sa môjho štýlu, tónu a slovníka
3. Vždy používaj pevný formát výstupu
4. Keď niečo chýba alebo nie je isté, povedz to a nepíš si fakty
5. Vlastná odpoveď
```

### Examples

```text
Máš dobrý príklad výstupu, podľa ktorého sa má skill učiť?

Vyber jednu možnosť, alebo napíš vlastnú:

1. Áno, pošlem jeden dobrý príklad (odporúčam, najviac zlepší kvalitu)
2. Mám skôr zlý príklad, ktorému sa má AI vyhnúť
3. Nemám príklad, použi pravidlá a neskôr ho doplním
4. Príklad je citlivý, radšej ho zhrniem vlastnými slovami
5. Vlastná odpoveď
```

### Gotchas

```text
Čo býva na tomto postupe najčastejšia chyba?

Vyber jednu možnosť, alebo napíš vlastnú:

1. AI znie príliš všeobecne alebo marketingovo
2. AI si domýšľa fakty, ceny alebo sľuby
3. AI preskočí dôležitý krok alebo kontrolu
4. AI nerozozná špeciálny prípad, ktorý má ísť človeku
5. Vlastná odpoveď
```

## Safety Questions

### Approval

```text
Kde musí skill pýtať tvoje schválenie?

Vyber jednu možnosť, alebo napíš vlastnú:

1. Pred odoslaním alebo publikovaním čohokoľvek navonok (odporúčam)
2. Pred zmenou ceny, zľavy alebo obchodných podmienok
3. Pred prácou s citlivými údajmi alebo VIP klientmi
4. Stačí pripraviť draft, všetko ostatné robím ja
5. Vlastná odpoveď
```

### Never

```text
Čo skill nesmie nikdy urobiť sám?

Vyber jednu možnosť, alebo napíš vlastnú:

1. Odoslať email, správu alebo ponuku klientovi
2. Publikovať obsah alebo meniť web / CRM / databázu
3. Sľúbiť cenu, termín, výsledok alebo právnu/finančnú radu
4. Spracovať citlivé údaje bez jasného dôvodu
5. Vlastná odpoveď
```

### External Inputs

```text
Bude skill čítať cudzie alebo externé vstupy?

Vyber jednu možnosť, alebo napíš vlastnú:

1. Áno, emaily alebo správy od klientov
2. Áno, PDF, web stránky alebo dokumenty od iných ľudí
3. Áno, exporty z CRM, tabuľky alebo interné dáta
4. Nie, bude pracovať len s tým, čo mu priamo zadám
5. Vlastná odpoveď
```

If yes, add prompt-injection warning and approval boundaries.

## Audience-Specific Ideas

Use these to make options feel personal to Majster Biznisu participants:

- reality: follow-up po obhliadke, odpoveď leadu, audit inzercie, vizualizácia rekonštrukcie
- elektro / automatizácie: cenová ponuka, technický intake, odovzdanie projektu, servisné odpovede
- betón / stavebné práce: dopyt, obhliadka, kalkulácia, projektové odovzdanie, interný report
- výrobca kľučiek: B2B dopyt, produktové poradenstvo, export/import otázky, obchodný follow-up
- zubárka: edukácia pacientov, odpovede na časté otázky, recenzie, pripomienky
- e-shop doplnky výživy: produktové poradenstvo, reklamné kreatívy, email kampane, FAQ
- investície / krypto / nehnuteľnosti: obsah, research, lead kvalifikácia, rizikové disclaimery
