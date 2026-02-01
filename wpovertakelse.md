# WP Overtakelse

> Ryddig overlevering av WordPress-sider

---

Når nettsiden er ferdig, begynner misforståelsene.

*"Hva var inkludert igjen?"*
*"Hvem har ansvar for dette?"*
*"Sto det ikke i mailen at...?"*

**WP Overtakelse løser dette.**

---

## Hva det er

| | |
|---|---|
| **Type** | WordPress-plugin |
| **Formål** | Strukturert overlevering |
| **Brukere** | Utvikler → Kunde |
| **Output** | Låst, lesbart dokument |

---

## Hvordan det fungerer

```
┌─────────────────────────────────────────┐
│  UTVIKLER                               │
│  ─────────                              │
│  1. Fyller inn overleveringsrapport     │
│  2. Låser dokumentet                    │
│                                         │
│              ↓                          │
│                                         │
│  KUNDE                                  │
│  ─────                                  │
│  3. Får tilgang til lesbart dokument    │
│  4. Ser tydelig:                        │
│     ✓ Hva som er levert                 │
│     ✗ Hva som ikke er inkludert         │
│     → Hvem som har ansvar videre        │
└─────────────────────────────────────────┘
```

---

## Innhold i rapporten

| Seksjon | Beskrivelse |
|---------|-------------|
| **Levert** | Konkret liste over hva som er bygget og konfigurert |
| **Ikke inkludert** | Tydelig avgrensning av hva som *ikke* er del av leveransen |
| **Ansvar** | Hvem som håndterer hva fremover (drift, oppdateringer, innhold) |
| **Tilganger** | Oversikt over kontoer og pålogginger (om relevant) |
| **Notater** | Eventuelle spesielle hensyn eller instruksjoner |

---

## Nøkkelegenskaper

- **Kan ikke endres** — dokumentet låses ved ferdigstilling
- **Felles referansepunkt** — begge parter ser det samme
- **Ikke-juridisk** — tydelig uten å bli kontraktsmessig
- **Enkelt** — ingen opplæring nødvendig

---

## Filosofi

> God overlevering handler ikke om å dekke seg.
> Det handler om å være tydelig.

WP Overtakelse reduserer friksjon mellom utvikler og kunde — ikke med juridiske klausuler, men med klarhet.

---

<details>
<summary><strong>Teknisk</strong></summary>

- Custom Post Type for overleveringer
- Låsemekanisme som forhindrer redigering
- Kundevisning uten admin-tilgang
- Eksport til PDF (valgfritt)

</details>
