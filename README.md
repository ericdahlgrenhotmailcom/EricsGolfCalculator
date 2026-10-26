# EricsGolfCalculator

Ett C#/.NET-projekt som räknar ut hur långt ett golfslag faktiskt spelas baserat på väder och terräng.

## Vad appen gör

I stället för att bara titta på avståndet till flaggan tar kalkylatorn hänsyn till de yttre faktorer som påverkar bollen:

- **Höjdskillnad:** Justerar avståndet baserat på om slaget spelas uppför eller utför.
- **Vind:** Delar upp vindhastighet och vindriktning i medvind, motvind och sidvind.
- **Temperatur:** Tar hänsyn till att kall luft ger kortare slag och varm luft ger längre bärighet.
- **Klubbval:** Ger förslag på lämplig klubba utifrån det beräknade spelavståndet.

## Tekniker

- C# / .NET
- Matematisk logik och vektorer för vindberäkningar
- Konsolapplikation / Logikmodul

## Så kör du projektet

1. Klona repot:
   ```bash
   git clone [https://github.com/ericdahlgrenhotmailcom/EricsGolfCalculator.git](https://github.com/ericdahlgrenhotmailcom/EricsGolfCalculator.git)
