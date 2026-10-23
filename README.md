# Fagner Raquetes

Site institucional da **Fagner Raquetes**: venda de raquetes de tênis novas e seminovas, trocas, acessórios e encordoamento especializado, com envio para todo o Brasil.

- Instagram: [@fagner.raquetes](https://www.instagram.com/fagner.raquetes/)
- WhatsApp: (11) 94710-6033
- Loja: Rua Antônio Macedo, 190 · Parque São Jorge, São Paulo/SP

## Estrutura

Página única e estática, sem dependências de build. Tudo está em `index.html` (HTML, CSS e JavaScript); as fontes vêm do Google Fonts.

Seções: início com raquete interativa (canvas), serviços, encordoamento com montador que envia as escolhas pelo WhatsApp, vitrine, estoque (pares anunciados no Instagram, com ficha técnica), quem sou eu, envio, comunidade e contato.

As fotos do estoque ficam em `img/estoque/` e os dados de cada par na lista `STOCK` dentro do `index.html`. Para atualizar o estoque, troque a foto e edite a entrada correspondente.

## Rodar localmente

Abra o `index.html` no navegador, ou sirva a pasta:

```bash
python3 -m http.server 8000
```

## Publicar no GitHub Pages

Settings → Pages → Source: *Deploy from a branch* → Branch `main`, pasta `/ (root)`.

## Próximos passos

- Substituir as ilustrações da vitrine e do "Quem sou eu" por fotos reais da loja e do Fagner.
- Trocar o logo vetorial redesenhado pelo arquivo original em alta resolução.
