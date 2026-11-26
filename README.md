# Calcul priză de pământ

Aplicație web (HTML static) pentru calculul prizei de pământ, după relațiile din normativul I7-2011, Anexa 5.34.

- Antet de proiect: Beneficiar, Adresa, Proiectant, Nr. Proiect, Faza, Data
- Etapele de calcul cu formule afișate algebric (editabile)
- Factori de utilizare preluați din tabelul A5.34-5
- Schiță în plan și animație în secțiune
- Breviar de calcul: tipărire sau descărcare PDF (A4), cu secțiuni selectabile

## Fișiere

- `index.html` – aplicația
- `pdf-fonts.css` – fonturile Barlow incluse pentru generarea PDF-ului
- `jspdf.umd.min.js` – biblioteca jsPDF 2.5.1 (licență MIT) pentru PDF

## Publicare pe Vercel

1. Vercel → Add New… → Project → importă acest repository.
2. Framework Preset: **Other**. Fără build command, Output Directory: rădăcina (`.`).
3. Deploy.
