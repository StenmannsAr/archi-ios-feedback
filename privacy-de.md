# Datenschutzerklärung – Archi

**Stand: Mai 2026**

---

## Grundsatz: Keine Datenerhebung

Archi erhebt, speichert oder überträgt **keine personenbezogenen Daten**
an den App-Entwickler oder Dritte. Die App wurde nach dem Prinzip
„Privacy by Design" entwickelt.

---

## Was auf dem Gerät passiert

Alle Kernfunktionen laufen vollständig lokal auf dem iPhone des Nutzers:

- **Kamera-Scans** werden ausschließlich lokal verarbeitet und nie an externe Server übertragen
- **OCR (Texterkennung)** läuft über Apple Vision vollständig auf dem Gerät
- **KI-Analyse** (Metadatenextraktion) läuft über Gemma 4 (LiteRT) vollständig auf dem Gerät
- **Server-URL und API-Token** werden ausschließlich im iOS Keychain des Nutzers gespeichert —
  der Entwickler hat keinen Zugriff darauf

---

## Was optional übertragen wird

Nur wenn der Nutzer einen eigenen Paperless-NGX-Server konfiguriert, werden
gescannte Dokumente **direkt und ausschließlich** an diesen Server übertragen.

- Die Verbindung erfolgt direkt zwischen iPhone und dem nutzereigenen Server
- Der Entwickler ist an keinem Zeitpunkt an dieser Verbindung beteiligt
- Der Entwickler hat keinen Zugriff auf den Server oder die übertragenen Dokumente

---

## Keine Tracker und keine Analytics

Archi enthält:

- Keine Tracking-SDKs (kein Firebase, kein Crashlytics, kein Amplitude o.ä.)
- Keine Analytics-Dienste
- Keine Werbenetzwerke
- Keine In-App-Käufe außer dem einmaligen App-Kauf über Apple

---

## Apple App Store

Der einmalige Kauf der App (0,99 €) wird über Apple Inc. abgewickelt.
Dabei gelten die Datenschutzbestimmungen von Apple:
https://www.apple.com/de/legal/privacy/

---

## Kontakt

Bei Fragen zum Datenschutz:

**Arne Stenmanns**
E-Mail: arne.stenmanns@mailbox.org
