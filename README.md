# mimopetofertas.com.br

Public GitHub Pages site for **MimoPet Ofertas**.

The office package stays private: https://github.com/PauloLinhares09/Mimopet-Ofertas

Do not copy `company/`, `agents/`, or `tech/` here.

Canonical URL: https://www.mimopetofertas.com.br/ (HTTPS enforced; custom-domain cert issued 2026-09-15).

WhatsApp / Open Graph: `og:url` and `og:image` are HTTPS on this host (`assets/img/og-cover.jpg`, 1200×630).

## Gitflow

- Production: **`master`** (GitHub Pages source `/`)
- Integration: **`develop`**
- Features: `feature/*` → PR into `develop` → release PR into `master`

## v1

Static one-pager + `privacidade.html`. Telegram CTA is disabled (“em breve”). No prices, SKUs, or invented handles.

**v0.3.0:** `#lojas` names platforms we may watch (Cobasi piloto; Petz/Amazon/ML/Shopee informal). Design tokens and hero copy unchanged.

**v0.3.1:** Custom-domain TLS live; Open Graph URL/image on `https://www.mimopetofertas.com.br/` so WhatsApp can scrape title, description, and cover.
