# Tilbakemelding på product brief

| | |
|---|---|
| **Gruppe** | G17 – G17-mehjez |
| **Product brief** | Ingen product brief funnet på main (siste commit e6a11bf) |
| **Tilbakemelding fra** | Faglærer i IBE160 (utarbeidet med KI-støtte) |
| **Dato** | 2026-10-06 |

## Samlet vurdering

- **Bør revideres før dere går videre.** Lag en product brief før dere lager PRD og arkitektur.

Det ble ikke funnet noen product brief på main per 2026-10-06. Repoet inneholder bare `README.md` og `.gitignore` fra opprettelsen av gruppeprosjektet, og det finnes ingen commits etter den første. Vi fant heller ikke andre spor av en prosjektidé, for eksempel en beskrivelse i README eller i commit-meldinger. Derfor kan vi ikke gi en foreløpig vurdering av vanskelighetsgrad eller gjennomførbarhet ennå.

## Hvorfor product brief er viktig for mappen

Product brief er utgangspunktet for PRD, arkitektur, stories og til slutt koden. Del 1 av mappen vurderes blant annet på om sensor kan følge en sporbar vei fra plan til ferdig app. Den vurderes også på om appen gjør det dere har beskrevet, om den er testet, om den er godt designet, og om den kan kjøres etter README. Uten en brief mangler første ledd i denne kjeden, og prosess og KI-styring er det kriteriet som teller mest i del 1 (30 %). Det er mye enklere å rette nå enn sent i semesteret.

## Hva briefen bør inneholde

Lag briefen med BMAD (for eksempel skillen `bmad-product-brief`) og legg den i repoet, gjerne under `_bmad-output/planning-artifacts/briefs/`. Faglærers eksempelprosjekt viser hele flyten fra brief via PRD og arkitektur til stories og kode: https://github.com/IBE160-2026/beergame.

Briefen bør ha disse delene:

| Del av brief | Hva den bør svare på |
|---|---|
| Executive Summary | Hva er appen, og hvilket problem løser den? To–tre setninger. |
| The Problem | Hvilken konkret situasjon og hvilke brukere har problemet i dag? |
| The Solution | Hva gjør brukeren i appen? Beskriv kjerneflyten i 3–5 steg, ikke teknologien. |
| What Makes This Different | En ærlig vurdering av hva som finnes fra før, og hva appen gjør annerledes. |
| Who This Serves | Én tydelig primærbruker og hva hen trenger. |
| Success Criteria | Kriterier som kan sjekkes eller testes, for eksempel «brukeren kan registrere X og se det i oversikten». |
| Scope | Hva som er med i første versjon («In for v1»), og hva som ikke er det («Explicitly out»). |
| Vision | Hvor appen kan gå etter v1, uten at det blåser opp omfanget nå. |

I tillegg bør dere selv vurdere **vanskelighetsgrad og gjennomførbarhet**, og begrunne vurderingen:

- Sammenlign med forslagslista «Prosjektforslag for IBE160 Programmering med KI». Enkle prosjekter er for eksempel 1) AI Study Buddy og 6) To-do-liste med smarte etiketter. Middels prosjekter er 2) AI CV- og søknadsassistent og 7) Kurs-FAQ-chatbot. Vanskelige prosjekter er 3) simulering av prosjektledelse, 4) MRP II og 5) KI-styrt sensurering.
- Vurder om dere kan kontrollere at koden Claude Code lager, gir riktige svar, og om det finnes tydelige regler som tester kan skrives mot.
- Vurder om sensor kan kjøre appen lokalt etter README, uten deres nøkler eller betalte kontoer. Bruker appen en språkmodell, trenger dere en plan for testmodus eller mock-svar.
- Vurder om v1 rekker å bli ferdig og stabil med tid til hele BMAD-flyten, testing og README.

Er dere usikre på idé, kan dere velge et av forslagene fra lista og avgrense det. Et enkelt prosjekt gir god sjanse for å bli ferdig, men krever mer i design, testing og dokumentert prosess for å nå helt opp.

## Neste steg for gruppen

1. Velg prosjektidé snarest, enten egen idé eller et forslag fra lista, og kjør `bmad-product-brief` for å lage briefen.
2. Commit briefen til repoet, og be gjerne om en ny tilbakemelding før dere går videre.
3. Gå deretter videre til PRD og arkitektur. Commit underveis, slik at historikken viser hvordan planen utviklet seg.

Det er en del av prosessen sensor ser etter at planleggingsdokumentene ligger i repoet og oppdateres over tid.
