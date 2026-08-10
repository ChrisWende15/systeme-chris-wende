# systeme.chris-wende.com

Eigenständige Landingpage der Wende High Performance Consulting GmbH:
**Onboarding-Systeme, Wissensdatenbank & KI-Chatbot für KMU.**

Statische Website (reines HTML/CSS, keine Abhängigkeiten, keine Cookies,
Schrift Raleway selbst gehostet = DSGVO-freundlich).

## Struktur

- `index.html` – die komplette Seite (alle Texte)
- `assets/css/style.css` – Design (Farben/Schrift von chris-wende.com übernommen)
- `assets/img/` – Logos, Presse-Logos, Fotos (Quelle: chris-wende.com)
- `assets/fonts/` – Raleway (variabel, Latin, selbst gehostet)
- `CNAME` – Wunsch-Domain für GitHub Pages: `systeme.chris-wende.com`

## Lokal ansehen

```bash
python3 -m http.server 8777 -d . 
```

Dann im Browser: http://localhost:8777

## Veröffentlichen (GitHub Pages)

1. Repository auf GitHub anlegen (z. B. `systeme-chris-wende`) und pushen.
2. Repo → Settings → Pages → Source: Branch `main`, Ordner `/ (root)`.
3. Beim Domain-Anbieter einen CNAME-Eintrag anlegen:
   `systeme.chris-wende.com` → `<github-benutzername>.github.io`
4. In den Pages-Einstellungen die Custom Domain `systeme.chris-wende.com`
   eintragen und „Enforce HTTPS" aktivieren.

Der Buchungs-Button verlinkt auf
https://www.chris-wende.com/kostenfreies-erstgespraech/ –
Impressum und Datenschutz ebenfalls auf die Hauptseite.
