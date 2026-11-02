# Imagini portofoliu

Pune aici capturile de ecran ale site-urilor, cu EXACT aceste nume de fișier
(sunt deja legate în `index.html`):

| Fișier                      | Site                              |
|-----------------------------|-----------------------------------|
| `toroscarol.jpg`            | toroscarol.ro                     |
| `sturz.jpg`                 | sturz.ro                          |
| `magnumteam.jpg`            | magnumteam.ro                     |
| `emilys.jpg`                | emilys.ro                         |
| `scoaladeatasament.jpg`     | scoaladeatasament.ro              |
| `capcanelegandirii.jpg`     | capcanelegandirii.toroscarol.ro   |

De adăugat acum: `scoaladeatasament.jpg` și `capcanelegandirii.jpg`
(celelalte sunt deja urcate).

## Recomandări
- Format: **JPG** (sau PNG, dar atunci schimbă și extensia în `index.html`).
- Dimensiune ideală: **~1200 × 750 px** (raport 16:10). Nu e obligatoriu exact —
  imaginea e tăiată automat (`object-fit: cover`), dar 16:10 arată cel mai bine.
- Greutate: ideal sub ~300 KB/imagine, ca site-ul să încarce repede.

## Cum le adaugi (deploy prin GitHub → Vercel)
Cel mai simplu, din interfața GitHub:
1. Intră în repo → deschide folderul `images`.
2. Apasă **Add file → Upload files**.
3. Trage fișierele (cu numele de mai sus) și **Commit changes**.

Vercel redeployează automat, iar imaginile apar în portofoliu. Cât timp un fișier
lipsește, cardul afișează un placeholder discret (nu o imagine „ruptă").
