# Site da Dra. Julia Umeoka

Demonstração: https://paparidisbrancher.github.io/dra-julia-umeoka/

Site estático, sem etapa de build. `index.html` e `privacidade.html` usam o runtime `support.js`, com o React 18.3.1 servido de `vendor/` (sem CDN). Fontes em `fonts/` e imagens em `assets/`.

## Editar

- WhatsApp, mensagem inicial e Instagram: objeto `CONTATO` no script do `index.html`.
- Perguntas frequentes: ao mudar uma pergunta ou resposta, atualize também o bloco `FAQPage` no `<head>` do `index.html`.

## Publicar no domínio próprio

1. Trocar `https://paparidisbrancher.github.io/dra-julia-umeoka/` pelo domínio novo no `index.html` (canonical, og:url, og:image, twitter:image e dados estruturados), no `robots.txt` e no `sitemap.xml`.
2. No `index.html`, trocar `noindex, nofollow` por `index, follow, max-image-preview:large`.
3. Cadastrar o domínio no Google Search Console e enviar o `sitemap.xml`.
4. Criar o Perfil da Empresa no Google com nome, telefone e clínica escritos exatamente como no site.

## Pendências da cliente

- Logo original (SVG ou PNG transparente) e confirmação das cores com a designer.
- Endereço completo da Clínica Prevent Cor (mapa e dados estruturados), horários e convênios.
- Aprovação dos textos pela médica.
