# mindra-site

Site institucional da **MINDRA** — consultoria em Inteligência Artificial e criação de sites para empresas.

## Stack

Site estático em um único `index.html` (HTML + CSS + JavaScript vanilla, sem dependências de build).

## Estrutura

- `index.html` — página completa (head com SEO/Open Graph, estilos e scripts inline)
- `manifest.webmanifest` — manifesto PWA (instalação no celular)
- `assets/` — favicons, ícones (192/512px, maskable, apple-touch) e imagem de compartilhamento OG (1200×630)
- `robots.txt` e `sitemap.xml` — diretrizes para buscadores

## Seções

Hero · Problema · Como trabalhamos · Serviços · **Criação de sites** · **Planos** · Aplicações de IA · Diferencial · Sobre · **Dúvidas frequentes (FAQ)** · Contato · Rodapé

## Funcionalidades

- Formulário de contato com validação, máscara de WhatsApp, integração FormSubmit + Google Apps Script
- Tabs acessíveis (ARIA), menu mobile, animações com `prefers-reduced-motion`
- FAQ em accordion nativo (`<details>`) com schema `FAQPage`
- Schema JSON-LD `Organization`, `WebSite` e `FAQPage`
- Open Graph/Twitter Cards e ícones PWA

## Rodar localmente

```bash
python3 -m http.server 8080
# ou
npx serve
```
