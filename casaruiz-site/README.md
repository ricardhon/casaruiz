# Casa Ruiz — site

Site estático (HTML + CSS puro, sem framework). Publicação: Netlify.

## Estrutura
```
index.html            Início
diagnostico/           Oferta paga — 850 €
metodo/                 Os quatro pilares
casos/                  Índice de casos
casos/evaderm/         Caso EvaDerm
sobre/                  Ricardo Ruiz
contacto/               WhatsApp + email
en/                     Inglês (só a inicial, por agora)
assets/style.css        Estilo único, todas as páginas
llms.txt                Descrição do site para agentes de IA
robots.txt              Liberta explicitamente crawlers de IA
sitemap.xml             Mapa do site
netlify.toml            Configuração de publicação
```

## Publicar
1. Enviar esta pasta para um repositório GitHub.
2. Ligar o repositório a um novo site Netlify.
3. Apontar `casaruiz.pt` para o Netlify (Cloudflare DNS → CNAME/A conforme instruções do Netlify).
4. Confirmar HTTPS automático (Netlify trata disto).

## Por fazer antes de publicar
- [ ] Substituir placeholders de contacto se mudarem
- [ ] Confirmar preço do diagnóstico em `/diagnostico/index.html` e na home
- [ ] Verificar telefone do WhatsApp em `/contacto/`
- [ ] Adicionar Google Search Console (meta tag ou ficheiro de verificação)
- [ ] Adicionar GA4 quando decidido
- [ ] Página do caso Sushi do Edu, quando houver resultados
