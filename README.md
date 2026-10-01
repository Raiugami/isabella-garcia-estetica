# Isabella Garcia | Estética

Site institucional da **Isabella Garcia**, esteticista em Santo André (ABC paulista), com brow lamination, extensão de cílios (volume brasileiro e egípcio), lash lifting, limpeza de pele e Hidragloss.

- **Cliente:** Isabella Garcia
- **Site publicado:** https://raiugami.github.io/isabella-garcia-estetica/
- **Instagram:** [@beautyisagarcia](https://www.instagram.com/beautyisagarcia)

## Sobre o projeto

Página única (one-page), responsiva, criada para apresentar os serviços e levar o visitante ao agendamento. O botão de agendar leva ao direct do Instagram; para usar WhatsApp, basta preencher o número no script do final do `index.html`.

Seções: apresentação, sobre, serviços, passo a passo do agendamento, resultados (posts do Instagram), feedbacks de clientes, localização (mapa do bairro Campestre) e dúvidas frequentes.

## Tecnologias

- HTML5 e CSS3 puros e JavaScript puro, em um único arquivo, sem build e sem dependências
- Fotos embutidas no próprio HTML (base64)
- Google Fonts: Cormorant Garamond e Jost
- Embeds do Instagram e do Google Maps
- Hospedagem: GitHub Pages

## Estrutura de pastas

```
.
├── index.html   # página única do site (estilos, imagens e scripts embutidos)
└── README.md
```

## Como personalizar

No `<script>` do final do `index.html`:

- `WHATSAPP`: número com DDI+DDD, só dígitos (ex.: `"5511999999999"`). Vazio, os botões levam ao direct do Instagram.
- `INSTAGRAM`: usuário do Instagram.
- `MENSAGEM`: texto pronto do WhatsApp.

Preços não foram incluídos de propósito. Os feedbacks são trechos de mensagens publicadas nos destaques, sem nome, e devem ser autorizados pela cliente.

## Como rodar localmente

Abra o `index.html` no navegador, ou use um servidor local:

```bash
python -m http.server 8000
```

Depois acesse http://localhost:8000.

## Publicação

O site é publicado pelo GitHub Pages a partir da branch `main`, pasta raiz. Qualquer push na `main` atualiza o site em poucos minutos.
