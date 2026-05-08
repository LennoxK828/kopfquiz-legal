# Datenschutzerklärung — Kopfquiz

**Stand:** 25. April 2026
**Verantwortlich:** Lennox Kornmann · kopfquiz123@gmail.com

## Kurzfassung

Kopfquiz ist eine Kopfrechen-Trainings-App. Die meisten Daten bleiben **lokal auf deinem iPhone**. Wir verwenden Werbung (Google AdMob) und einen Cloud-Backend (Supabase) für Score-Synchronisation. Keine Datenweitergabe an Dritte außerhalb der unten genannten Dienstleister.

---

## 1. Welche Daten werden lokal verarbeitet?

Folgende Daten werden ausschließlich auf deinem Gerät gespeichert (UserDefaults, lokale Datenbank):

- **Profildaten:** Name, Avatar, Level, XP, Trophäen, Streaks, Herzen
- **Spielfortschritt:** abgeschlossene Aufgaben, Fehlerstatistik, Achievements, Daily-Challenge-Resultate
- **Einstellungen:** App-Konfiguration, Freundecodes, Erinnerungs-Timer
- **Genius-Coach-Analysen:** werden vollständig **on-device** mit Apple Intelligence (Foundation Models, iOS 26+) erstellt. Deine Fehler verlassen dein Gerät nicht.

## 2. Welche Daten werden an Server übertragen?

### Supabase (Cloud-Datenbank, EU-Region)
Wenn du dich mit einem Konto einloggst und Score-Sync aktiv ist, übertragen wir:
- Spielergebnisse (Score, Streak, Dauer, Modus)
- Account-Identifier (E-Mail oder Provider-ID)

**Anbieter:** Supabase, Inc. — Server in der EU.
**Zweck:** Cross-Device-Sync, anonymisierte Bestenlisten.
**Rechtsgrundlage:** Art. 6 Abs. 1 lit. b DSGVO (Vertragserfüllung).

### Google AdMob (Werbung)
Wir zeigen Werbung von Google AdMob an Nicht-Premium-Nutzern. AdMob verarbeitet:
- Werbe-Identifier (IDFA, falls du in ATT zugestimmt hast)
- Allgemeine Geräteinformationen (iOS-Version, Sprache, ungefährer Standort über IP)

**Anbieter:** Google Ireland Limited, Gordon House, 4 Barrow St, Dublin, D04 E5W5, Irland.
**Zweck:** Anzeigen-Auslieferung und Frequency-Capping.
**Rechtsgrundlage:** Art. 6 Abs. 1 lit. a DSGVO (Einwilligung über ATT).
**Mehr Infos:** https://policies.google.com/privacy

### Apple App Store (StoreKit)
Käufe (Lifetime-Unlock, Heart-Refill) werden über Apple StoreKit verarbeitet. Wir erhalten nur die Transaktion zur Freischaltung — keine Zahlungsdaten.

## 3. App Tracking Transparency (ATT)

Beim ersten App-Start fragen wir dich, ob du personalisierte Werbung erlauben möchtest. **Lehnst du ab, wird die App weiter funktionieren** — du siehst dann nur unpersonalisierte Werbung.

## 4. Genius AI Coach

Der Genius-Coach analysiert deine Fehler **vollständig auf deinem iPhone** mit Apple Intelligence (iOS 26+). Wenn dein Gerät Apple Intelligence nicht unterstützt, läuft eine lokale Heuristik. **In keinem Fall werden Fehler-Daten an Server übertragen.**

## 4a. Auftragsverarbeitung & Datentransfer (Art. 28 DSGVO)

Folgende Dienstleister verarbeiten Daten in unserem Auftrag. Mit jedem dieser Dienstleister besteht — soweit anwendbar — ein Auftragsverarbeitungsvertrag (AVV) gemäß Art. 28 DSGVO.

| Dienstleister | Verarbeitete Daten | Standort | Rechtsgrundlage des Drittlandstransfers |
|---|---|---|---|
| Supabase, Inc. | Account-Identifier, Spielergebnisse | EU-Region (Frankfurt) | EU-intern, kein Drittlandstransfer |
| Apple Inc. (StoreKit, App Store Server Notifications) | Transaktions-IDs, App Account Token (anonyme UUID) | EU/USA | Standardvertragsklauseln (SCC), Apple ist DPF-zertifiziert |
| Google Ireland Ltd. (AdMob) | IDFA (nur bei ATT-Zustimmung), grobe Geräteinfos | EU/USA | Standardvertragsklauseln (SCC), Google LLC ist DPF-zertifiziert |

Supabase setzt zur Bereitstellung des Dienstes ihrerseits Subdienstleister ein (z. B. AWS für Hosting). Eine vollständige Liste der Subdienstleister sowie das DPA findest du unter <https://supabase.com/legal/dpa>.

**On-device-Verarbeitung (Apple Intelligence / Foundation Models):** Genius-Coach-Analysen werden ausschließlich lokal auf deinem Gerät erstellt. Es findet keine Verarbeitung durch externe Anbieter statt — auch nicht durch Apple-Server.

## 5. Deine Rechte (DSGVO)

- **Auskunft** über gespeicherte Daten (Art. 15 DSGVO)
- **Berichtigung** (Art. 16 DSGVO)
- **Löschung** (Art. 17 DSGVO)
- **Einschränkung** (Art. 18 DSGVO)
- **Datenübertragbarkeit** (Art. 20 DSGVO)
- **Widerspruch** (Art. 21 DSGVO)
- **Beschwerde** bei der zuständigen Aufsichtsbehörde

Anfragen an: **kopfquiz123@gmail.com**

## 6. Lokale Daten löschen

In den App-Einstellungen unter "Konto" findest du die Funktion "Alle Daten löschen". Damit werden alle lokalen Daten und der Server-Account entfernt.

## 7. Kinder

Kopfquiz ist nicht primär für Kinder unter 13 Jahren konzipiert. Wir sammeln wissentlich keine Daten von Kindern. Wenn du Eltern bist und vermutest, dass dein Kind Daten übermittelt hat, kontaktiere uns für eine sofortige Löschung.

## 8. Änderungen

Wir können diese Datenschutzerklärung anpassen. Wesentliche Änderungen werden in der App angekündigt.
