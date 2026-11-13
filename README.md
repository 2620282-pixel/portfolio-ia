# Portfólio de IA · Fabiano Nicaretta

Seis projetos feitos com inteligência artificial, da ideia ao protótipo publicado, e a formação por trás deles. Portfólio apresentado na candidatura ao Programa de Trainee da Softplan.

**Ver a galeria:** https://2620282-pixel.github.io/portfolio-ia/

Contato: fabianonicaretta@gmail.com · Portfólio de propaganda: [behance.net/fabianonicaretta](https://www.behance.net/fabianonicaretta) · Compositor: [no Spotify](https://open.spotify.com/intl-pt/track/2dQkmG3GD2bFj7zY6MZ96u)

## Projetos

| Projeto | O que é | Feito com | Material na galeria |
|---|---|---|---|
| **Oráculo Particular** | App e baralho de autoconhecimento | Claude | Plano de negócios e 5 PDFs do baralho, cartas e ilustrações · [página do projeto](https://claude.ai/artifact/ULdGYxaZtEoYphWHLbZT5p) |
| **WANTED** | Rede social física de contracultura | Gemini Canvas | MVP com simulador de match, manifesto em vídeo, cartaz e estampas de camiseta |
| **Cupom Maníacos** | Projeto Integrador · ADS | Claude | Arquitetura do ecossistema e Smart Bot · [página do projeto](https://claude.ai/artifact/SHB3g21GkaFD7EpeGf81xs) |
| **S.O.S. Sidarta** | Sistema operacional Sidarta, produto-manifesto | IA generativa | Página do produto, 4 PDFs e cartazes |
| **Bit Sushi Hokusai** | Franquia fisital de sushi | Claude | Pitch de franquia, conceito phygital e UI do app · [página do projeto](https://claude.ai/artifact/VUzJDNQTmMF7C1j1S9r17T) |
| **Nova Pele Vecchietti** | Parceria público-privada para cultura | Claude | Apresentação, identidade visual, parecer jurídico e coleção de revestimentos · [página do projeto](https://claude.ai/artifact/HYzoyZpjhWtvhxK324kZQ8) |
| **Formação** | Currículo, diplomas e certificados | Claude (diagramação) | Currículo, caderno de certificados 2015–2023, TCC de Psicologia Transpessoal (Arte do Encontro), TCC de Publicidade e apresentação, Alquimia Individual |

## Como a galeria funciona

- Página única em HTML, CSS e JavaScript, sem build e sem dependências instaladas.
- Os PDFs abrem dentro da própria página com [PDF.js](https://mozilla.github.io/pdf.js/).
- As páginas do MVP do WANTED (`mvp/`) e do S.O.S. (`projetos/`) abrem em um leitor embutido.
- Funciona no celular: menu reorganizado, áreas de toque de 44 px e indicador de rolagem nas fichas.

## Estrutura

```
index.html      a galeria
docs/           PDFs de cada projeto
img/            capas, páginas e imagens dos projetos
media/          vídeo do manifesto WANTED
mvp/            MVP do WANTED
projetos/       página do S.O.S. Sidarta
```

## Rodar localmente

```bash
python -m http.server 8000
```

Depois abra http://localhost:8000.
