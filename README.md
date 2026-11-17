# Preču pārdošanas atskaišu veidotājs

Tīmekļa lietotne, kas izveido strukturētas Excel atskaites atbilstoši produkta kodiem (`KODI`) un realizācijas datiem (`REALIZ`).

## Galvenās funkcijas
- **100% pārlūkprogrammā:** dati netiek sūtīti uz ārējiem serveriem — visa apstrāde notiek lokāli lietotāja ierīcē.
- **Automātiska kolonnu sakārtošana:** failā `REALIZ` kolonnas `A–E` automātiski tiek nolasītas kā `KLIENTS`, `KODS`, `NOSAUKUMS`, `Daudzums` un `SUMMA`.
- **Produktu grupēšana:** viena produkta dažādie izdevumi tiek apvienoti vienā `.xlsx` failā katrs savā darba lapā (*sheet*).
- **Gatavs drukai:** katra darba lapa tiek automātiski noformēta drukai uz **1 A4 lapas portret (*Portrait*) režīmā**.

## Kā publicēt GitHub Pages
1. Augšupielādējiet šī arhīva failus (`index.html` un `README.md`) savā GitHub repozitorijā.
2. Repozitorijā atveriet **Settings** → **Pages**.
3. Sadaļā **Build and deployment** pie *Source* izvēlieties **Deploy from a branch**, norādiet zaru `main` (un mapi `/ (root)`) un nospiediet **Save**.
4. Pēc brīža lietotne būs pieejama tiešsaistē visiem lietotājiem caur jūsu GitHub Pages saiti.
