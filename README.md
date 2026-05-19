# Zrozum siebie. Działaj inaczej.

Landing page programu psychoedukacyjnego dla osób z ADHD i ich bliskich.

5 spotkań online live prowadzonych przez Aleksandra Koniecznego (psychologa MindWell Kraków) - od finansów po relacje. Pierwsze spotkanie "Finanse" za 37 zł, 11 czerwca 2026. Pakiet 5 spotkań w cenie 347 zł (wczesny dostęp do 11.06) / 447 zł.

## Stack

- Plain HTML + Tailwind CSS (CDN)
- Bricolage Grotesque (Google Fonts)
- Lucide Icons (CDN)
- Vanilla JS - countdown, scroll reveal, nav scroll
- Bez frameworka, bez build steppa

## Struktura

```
zrozum-siebie/
├── index.html          landing (one-pager)
├── regulamin.html      regulamin sprzedaży
├── polityka.html       polityka prywatności
└── assets/
    └── aleksander.jpg  zdjęcie prowadzącego
```

## Deploy

Static hosting (Vercel / Cloudflare Pages / Netlify) - bez build configu.

## Płatności

Dwa Stripe Payment Links (do uzupełnienia w `STRIPE_LINKS` w `<script>` na końcu `index.html`):
- `probne` - 37 zł (Finanse 11.06)
- `pakiet` - 347 zł (wczesny dostęp) / 447 zł (standard)
