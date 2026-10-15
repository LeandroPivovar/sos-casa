# SOS Casa | Soluções para o seu lar

Site institucional da SOS Casa (marido de aluguel e serviços residenciais). HTML/CSS/JS estático, sem build.
Mesma estrutura dos outros sites da AROE, com as cores da arte do cliente: azul-marinho e amarelo, e cada
serviço com a sua cor, como no folheto.

```bash
npx --yes serve . -l 6520
```

## Estrutura

```
index.html
assets/
  css/styles.css
  js/main.js              menu mobile, formulário -> WhatsApp, FAQ, reveal ao rolar, ano do rodapé
  fonts/phosphor/         ícones Phosphor (woff2 local, licença MIT)
  img/favicon.svg         casa com raio, como na logo
```

Sem fotos: o hero tem a casa com o raio (SVG) e o selo "Garantia total".

## Dados usados (fonte: arte de divulgação do cliente)

| Campo | Valor |
|---|---|
| Nome | SOS Casa - Soluções para o seu lar |
| Frases | "Seu lar em boas mãos!", "Faz tudo para sua casa!", "Serviços residenciais com qualidade, agilidade e confiança", "Profissionalismo e respeito a cada atendimento", "Garantia total - serviço bem feito é com a gente!" |
| Serviços | Marido de aluguel, eletricista, bombeiro, pintor, montador, consertos em geral, e muito mais |
| WhatsApp | (24) 99882-4778 (`wa.me/5524998824778`), informado pelo Leandro (a faixa da arte está cortada) |

## Confirmar com o cliente

- **Região atendida:** a arte não cita cidade (DDD 24). O formulário pede bairro/cidade.
- **Horário de atendimento:** não informado. O site não cita horário.
- **"Bombeiro":** na arte é o bombeiro hidráulico (aquecedores, chuveiros e gás). Serviços com gás exigem
  profissional habilitado; confirmar como a empresa trabalha.
- **Garantia total:** o site repete a frase da arte e diz que as condições vêm no orçamento. Se houver prazo
  definido, vale destacar.
- **Logo e fotos:** pedir a logo em arquivo e fotos reais da equipe/serviços.

## Depoimentos

Não foram incluídos, para não publicar avaliações inventadas.

Fontes: Poppins, Nunito Sans e Caveat Brush (Google Fonts, OFL).
