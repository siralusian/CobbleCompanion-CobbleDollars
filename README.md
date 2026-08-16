# CobbleCompanion: CobbleDollars

[![ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/C3W0229LCP)

[🇩🇪 Deutsche Version weiter unten](#deutsch)

## English

Adds a CobbleDollars wallet right inside the companion: transfers, transaction history, and
Creative-mode time purchases. Part of the modular **CobbleCompanion** family for Cobblemon —
usable in both singleplayer and multiplayer, though the wallet naturally matters most once other
players (and an economy) are involved.

### What it does

Adds a dedicated **Wallet tab** to CobbleCompanion whenever the CobbleDollars mod is running on
the server:

- Your balance at a glance, right inside the companion window.
- Transfer money to other players.
- A transaction log of past payments.
- Creative time purchase: buy temporary creative mode with CobbleDollars (if enabled by the
  server — see `/companion admin creativedimensions` and `/companion gamemode` in the base mod's
  README).

### How to use it

Open the companion window (see [CobbleCompanion](https://github.com/siralusian/CobbleCompanion)'s
README for how) and switch to the **Wallet** tab — no separate command or keybind needed. It only
lights up once the CobbleDollars mod is actually loaded server-side; otherwise it shows as an
inactive placeholder.

**Dependencies:** CobbleCompanion: Basis (required), CobbleDollars (required — without it the
Wallet tab stays inactive).

### Building

No foreign mod jars ship in `libs/` for licensing reasons — place them there yourself before
building.

**Own dependency (build it yourself):**
- `CobbleCompanion-Basis-*.jar` — build from the
  [CobbleCompanion](https://github.com/siralusian/CobbleCompanion) repo with `./gradlew jar`, copy
  the result from `build/libs/` into `libs/` here.

**Required:**
- `Cobblemon-neoforge-*.jar` — [Modrinth](https://modrinth.com/mod/cobblemon) /
  [CurseForge](https://www.curseforge.com/minecraft/mc-mods/cobblemon)
- `CobbleDollars-neoforge-*.jar` — the CobbleDollars mod

### Other CobbleCompanion projects

- [CobbleCompanion](https://github.com/siralusian/CobbleCompanion) — the base mod this depends on.
- [CobbleCompanion: CobbleDollars/Create](https://github.com/siralusian/CobbleCompanion-CobbleDollars-Create) —
  adds Create stock-ticker and Content Observer integration on top of this.
- [CobbleCompanion: CobbleDollars/CustomNPCs](https://github.com/siralusian/CobbleCompanion-CobbleDollars-CustomNPCs) —
  adds CustomNPCs trader integration on top of this.
- [CobbleCompanion: CobblemonWorker](https://github.com/siralusian/CobbleCompanion-CobblemonWorker)
- [Create: Let's Do Automation](https://github.com/siralusian/CreateLetsDo) — unrelated standalone
  mod, automates Let's Do: Farm & Charm blocks with Create.
- [CobbleCompanion: AllInOne](https://github.com/siralusian/CobbleCompanion-AllInOne) — this
  module plus everything else, in one file.
- [CobbleCompanion: CobbleDollars-Bundle](https://github.com/siralusian/CobbleCompanion-CobbleDollarsBundle) —
  this module plus the Create/CustomNPCs integrations, in one file.

---

## Deutsch

CobbleDollars-Wallet direkt im Begleiter: Überweisungen, Transaktionsverlauf und
Creative-Zeitkauf. Teil der modularen **CobbleCompanion**-Familie für Cobblemon – nutzbar im
Singleplayer und auf Servern, wobei die Wallet naturgemäß erst mit anderen Spielern (und einer
Wirtschaft) richtig Sinn ergibt.

### Was es macht

Fügt CobbleCompanion einen eigenen **Wallet-Tab** hinzu, sobald die CobbleDollars-Mod auf dem
Server läuft:

- Kontostand auf einen Blick, direkt im Begleiter-Fenster.
- Überweisungen an andere Spieler.
- Transaktions-Log vergangener Zahlungen.
- Creative-Zeitkauf: temporären Kreativmodus gegen CobbleDollars erwerben (sofern vom Server
  aktiviert – siehe `/companion admin creativedimensions` und `/companion gamemode` im README der
  Basis-Mod).

### Benutzung

Öffne das Companion-Fenster (siehe README von
[CobbleCompanion](https://github.com/siralusian/CobbleCompanion) für das Wie) und wechsle zum
**Wallet**-Tab – kein eigener Befehl oder Keybind nötig. Der Tab aktiviert sich nur, wenn die
CobbleDollars-Mod tatsächlich serverseitig geladen ist, sonst bleibt er als inaktiver Platzhalter.

**Abhängigkeiten:** CobbleCompanion: Basis (erforderlich), CobbleDollars (erforderlich – ohne
diese Mod bleibt der Wallet-Tab inaktiv).

### Bauen

Aus Lizenzgründen liegen keine fremden Mod-Jars in `libs/` im Repo – du musst sie vor dem Bauen
selbst dort ablegen.

**Eigene Abhängigkeit (musst du selbst bauen):**
- `CobbleCompanion-Basis-*.jar` — aus dem [CobbleCompanion](https://github.com/siralusian/CobbleCompanion)-Repo
  mit `./gradlew jar` bauen, das Ergebnis aus `build/libs/` hierher nach `libs/` kopieren.

**Erforderlich:**
- `Cobblemon-neoforge-*.jar` — [Modrinth](https://modrinth.com/mod/cobblemon) /
  [CurseForge](https://www.curseforge.com/minecraft/mc-mods/cobblemon)
- `CobbleDollars-neoforge-*.jar` — die CobbleDollars-Mod

### Weitere CobbleCompanion-Projekte

- [CobbleCompanion](https://github.com/siralusian/CobbleCompanion) — die Basis-Mod, von der dieses
  Modul abhängt.
- [CobbleCompanion: CobbleDollars/Create](https://github.com/siralusian/CobbleCompanion-CobbleDollars-Create) —
  fügt darauf aufbauend Create-Lagerticker- und Content-Observer-Anbindung hinzu.
- [CobbleCompanion: CobbleDollars/CustomNPCs](https://github.com/siralusian/CobbleCompanion-CobbleDollars-CustomNPCs) —
  fügt darauf aufbauend CustomNPCs-Händler-Anbindung hinzu.
- [CobbleCompanion: CobblemonWorker](https://github.com/siralusian/CobbleCompanion-CobblemonWorker)
- [Create: Let's Do Automation](https://github.com/siralusian/CreateLetsDo) — unrelated standalone
  mod, automates Let's Do: Farm & Charm blocks with Create.
- [CobbleCompanion: AllInOne](https://github.com/siralusian/CobbleCompanion-AllInOne) — dieses
  Modul plus alles andere, in einer Datei.
- [CobbleCompanion: CobbleDollars-Bundle](https://github.com/siralusian/CobbleCompanion-CobbleDollarsBundle) —
  dieses Modul plus die Create-/CustomNPCs-Anbindung, in einer Datei.
