# Preču pārdošanas atskaišu veidotājs

Tīmekļa lietotne, kas izveido strukturētas Excel atskaites atbilstoši produkta kodiem (`KODI`) un realizācijas datiem (`REALIZ`).

## Galvenās funkcijas
1. **Atskaišu ģenerēšana:**
   - Automātiski pārsauc `REALIZ` kolonnas `A–E` uz `KLIENTS`, `KODS`, `NOSAUKUMS`, `Daudzums`, `SUMMA`.
   - Grupē viena produkta dažādos numurus vienā `.xlsx` failā katru savā darba lapā (*sheet*).
   - Noformē katru lapu drukai uz **1 A4 lapas portret (*Portrait*) režīmā**.
2. **Masveida izdruka (`2. Masveida izdruka` cilne):**
   - Ļauj izvēlēties vairākus `.xlsx` / `.xls` failus vienlaikus un nosūtīt pilnīgi visus to *sheet*-us uz printeri ar vienu klikšķi.
