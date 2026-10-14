# Poliklinika Bandić — web stranica

Statična stranica, bez builda.

**Live:** https://faruk-ui-ux.github.io/poliklinika-bandic/

## Struktura
- `index.html` — cijela stranica
- `support.js` — runtime koji stranica treba (ne brisati)
- `img/` — fotografije

## Objava na GitHub Pages
Već je uključeno za ovaj repozitorij (Settings → Pages → `main` / `(root)`).
Za novi repozitorij: uploaduj sadržaj ovog foldera u root, pa isto podesi.

Lokalno: otvori preko servera (npr. `npx serve .`), ne dvoklikom na fajl.

## Status / poznata ograničenja
Ovo je koncept, ne i produkcijska stranica:
- Kalendar i rezervacija termina su potpuno na frontend-u (nema backend-a) —
  kad posjetilac "potvrdi" termin, ta informacija se nigdje ne šalje
  (ne stiže ni mejl ni poruka kliniki). Treba dodati pravi backend
  (npr. mejl/webhook) prije nego što se koristi za stvarne pacijente.
- "Šta vas dovodi?" čekboksovi (sekcija prije forme za zakazivanje) su
  trenutno dekorativni, ne filtriraju niti šalju ništa.
- Linkovi "Karijera", "Naši radovi", "Politika privatnosti" i "Uslovi
  korištenja" u footeru su placeholderi (vode na vrh stranice).
- Cijene i imena doktora u sadržaju su primjer radi koncepta — provjeriti
  prije javnog lansiranja da odgovaraju stvarnim podacima klinike.
