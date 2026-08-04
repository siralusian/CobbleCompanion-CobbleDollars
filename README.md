# CobbleCompanion: CobbleDollars

Teil der **CobbleCompanion**-Familie — ein modulares Baukasten-System für Cobblemon-Server.
Siehe [Verwandte Module](#verwandte-module--related-modules) unten für alle Varianten.

**Kurzbeschreibung:**
CobbleDollars-Wallet direkt im Begleiter: Überweisungen, Transaktionsverlauf und
Creative-Zeitkauf.

## Beschreibung

Fügt CobbleCompanion einen eigenen **Wallet-Tab** hinzu, sobald die CobbleDollars-Mod auf dem
Server läuft:

- Kontostand auf einen Blick, direkt im Begleiter-Fenster.
- Überweisungen an andere Spieler.
- Transaktions-Log vergangener Zahlungen.
- Creative-Zeitkauf: temporären Kreativmodus gegen CobbleDollars erwerben (sofern vom Server
  aktiviert).

**Abhängigkeiten:** CobbleCompanion: Basis (erforderlich), CobbleDollars (erforderlich – ohne
diese Mod bleibt der Wallet-Tab inaktiv).

---

## English

**Summary:**
Adds a CobbleDollars wallet right inside the companion: transfers, transaction history, and
Creative-mode time purchases.

## Description

Adds a dedicated **Wallet tab** to CobbleCompanion whenever the CobbleDollars mod is running on
the server:

- Your balance at a glance, right inside the companion window.
- Transfer money to other players.
- A transaction log of past payments.
- Creative time purchase: buy temporary creative mode with CobbleDollars (if enabled by the
  server).

**Dependencies:** CobbleCompanion: Basis (required), CobbleDollars (required — without it the
Wallet tab stays inactive).

---

## Bauen / Building

Aus Lizenzgründen liegen keine fremden Mod-Jars in `libs/` im Repo – du musst sie vor dem Bauen
selbst dort ablegen.
*No foreign mod jars ship in `libs/` for licensing reasons — place them there yourself before
building.*

**Eigene Abhängigkeit (musst du selbst bauen) / Own dependency (build it yourself):**
- `CobbleCompanion-Basis-*.jar` — aus dem [CobbleCompanion](https://github.com/siralusian/CobbleCompanion)-Repo
  mit `./gradlew jar` bauen, das Ergebnis aus `build/libs/` hierher nach `libs/` kopieren.

**Erforderlich / Required:**
- `Cobblemon-neoforge-*.jar` — [Modrinth](https://modrinth.com/mod/cobblemon) /
  [CurseForge](https://www.curseforge.com/minecraft/mc-mods/cobblemon)
- `CobbleDollars-neoforge-*.jar` — CobbleDollars-Mod

## Verwandte Module / Related modules

- [CobbleCompanion](https://github.com/siralusian/CobbleCompanion) — Basis
- [CobbleCompanion: CobbleDollars/Create](https://github.com/siralusian/CobbleCompanion-CobbleDollars-Create)
- [CobbleCompanion: CobbleDollars/CustomNPCs](https://github.com/siralusian/CobbleCompanion-CobbleDollars-CustomNPCs)
- [CobbleCompanion: CobblemonWorker](https://github.com/siralusian/CobbleCompanion-CobblemonWorker)
- [CobbleCompanion: Create/Let's Do](https://github.com/siralusian/CreateLetsDo)
- [CobbleCompanion: AllInOne](https://github.com/siralusian/CobbleCompanion-AllInOne)
- [CobbleCompanion: CobbleDollars-Bundle](https://github.com/siralusian/CobbleCompanion-CobbleDollarsBundle)
