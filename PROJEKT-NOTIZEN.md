# Salua – Projektnotizen

## Allgemein
- **Projekt**: Salua – ME/CFS Gesundheitsplattform
- **Domain**: salua.health
- **Hosting**: GitHub Pages (Repo: ykyhpvsmz5-sketch/ykyhpvsmz5-sketch.github.io)
- **Inhaber**: Simon Feldmann
- **E-Mail**: kontakt@salua.health (Weiterleitung über Namecheap → iCloud)
- **GitHub**: ykyhpvsmz5-sketch

## Newsletter
- **Tool**: MailerLite (Free Plan, bis 1.000 Abonnenten)
- **MailerLite Login**: simon.tawingtsun@gmail.com (Google SSO)
- **Alter Newsletter**: Formspree (ID: xeerweje) – durch MailerLite ersetzt
- **MailerLite Account ID**: 2211435
- **Automation**: "Salua Willkommens-Email" – aktiv, sendet bei Formular-Anmeldung
- **Willkommens-Email**: Betreff "Willkommen bei Salua – Du bist nicht allein", Absender "Salua"
- **Double Opt-in**: Aktiviert (DSGVO-konform)
- **Ziel**: Professioneller ME/CFS Newsletter mit Willkommens-Email und regelmäßigen Updates

## E-Mail Setup
- **kontakt@salua.health** → Weiterleitung über Namecheap Email Forwarding
- **Ziel**: iCloud Mail (simontawt@icloud.com)
- **Salua-Ordner**: In iCloud Mail erstellt, Mail-Regel muss noch gefixt werden

## Impressum
- **Status**: Noch kein Gewerbe angemeldet, Website im Aufbau
- **Aktuelle Angabe**: Name + E-Mail (nicht-kommerziell)
- **Adresse für MailerLite**: Dortmund, Germany
- **TODO**: Vollständige Adresse nach Gewerbeanmeldung ergänzen

## DNS (Namecheap)
- A Records: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
- CNAME: www → ykyhpvsmz5-sketch.github.io.
- HTTPS: Aktiviert

## Website-Struktur
- index.html (Hauptseite)
- histamin.html ("Was kann ich essen?" PWA)
- manifest.json + sw.js (PWA)
- impressum.html, datenschutz.html, medizinischer-hinweis.html
- themen/: diagnose, pacing, ernaehrung, psyche, forschung, behandlung, alltag, komorbiditaeten, rechte

## Erledigte Aufgaben
- [x] MailerLite eingerichtet (Account, Formular, Automation)
- [x] Willkommens-Email erstellt und Automation aktiviert
- [x] Website-Newsletter-Formular auf MailerLite umgestellt (index.html)
- [x] Impressum rechtlich angepasst (nicht-kommerziell, Name + E-Mail)
- [x] Website-Änderungen auf GitHub gepusht

## Offene Aufgaben
- [ ] iCloud Mail-Regel für Salua-Ordner fixen (jetzt MailerLite-Absender filtern)
- [ ] Impressum nach Gewerbeanmeldung vervollständigen
- [ ] Newsletter-Strategie & Content-Plan erstellen
- [ ] GitHub PAT Token löschen (Sicherheit)
