# AI Negotiator — MVP

## Cel
Automatyczne negocjowanie ceny między kupującym a sprzedawcą.

## Zasady MVP
1. Kupujący składa ofertę początkową
2. AI sprawdza różnicę względem ceny startowej
3. Jeśli oferta < 80% ceny startowej → AI odrzuca
4. Jeśli 80–95% → AI składa kontrofertę
5. Jeśli ≥ 95% → AI akceptuje

## Przykład
- Cena startowa: 1 000 €
- Oferta: 850 €
→ AI odpowiada: 950 €

## Prowizja
Platforma pobiera 20% od ceny zaakceptowanej przez AI.
