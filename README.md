# Missão Orangotango · Escape room

Escape room digital para o 3.º ciclo e o secundário.

**Pergunta da missão:** De que forma a compra de doces pode afetar as populações de orangotangos no seu habitat natural?

## Como publicar no GitHub Pages

1. Criar um repositório novo no GitHub (por exemplo, `missao-orangotango`).
2. Carregar o ficheiro `index.html` (e, se quiser, a imagem da notícia) para o repositório: *Add file → Upload files*.
3. Ir a *Settings → Pages*. Em *Source*, escolher *Deploy from a branch*, depois o ramo `main` e a pasta `/ (root)`. Guardar.
4. Ao fim de um ou dois minutos, o site fica disponível em `https://O-SEU-UTILIZADOR.github.io/missao-orangotango/`.

## Modo professor

Acrescente `?professor` ao fim do endereço, por exemplo:
`https://O-SEU-UTILIZADOR.github.io/missao-orangotango/?professor`

Aparece, em cada sala, um painel com as respostas e as pontes para a aula teórica, e um botão para saltar salas.

## Usar a imagem de uma notícia real

Por defeito, aparece a notícia do ficheiro `noticia-jornal.svg`. Para usar a imagem de uma notícia verdadeira:

1. Carregar a imagem para o repositório (por exemplo, `noticia.jpg`).
2. No `index.html`, alterar a linha `const IMAGEM_NOTICIA = "";` para `const IMAGEM_NOTICIA = "noticia.jpg";`.

Confirme que tem autorização para usar a imagem.

## Ficheiros

- `index.html`: a escape room completa (o rótulo já está incluído no próprio ficheiro).
- `noticia-jornal.svg`: o início da notícia, que abre a missão (adaptado e traduzido de um artigo do HuffPost). Só mostra o título e a entrada, para abrir a pergunta sem dar a resposta.
- `noticia-completa.svg`: a notícia completa, que só aparece depois do cadeado final, para os alunos a compararem com a sua explicação.
- `rotulo-chocolate.svg`: o rótulo fictício de um chocolate, usado na sala 3.

A notícia e o rótulo já estão incluídos no `index.html`; os ficheiros `.svg` servem para os links "Ver em tamanho grande" e para imprimir ou usar noutros materiais. Carregue todos os ficheiros para o repositório.

## Estrutura

| Sala | Desafio | Ponte para a teoria | Letra |
|---|---|---|---|
| 1 | Hipótese inicial (sem resposta certa) | Abrir diferenças | B |
| 2 | Palavras e significados científicos | Linguagem científica | O |
| 3 | Decifrar o rótulo de um chocolate | Entidades | R |
| 4 | Ordenar a cadeia de causa e efeito | Entidades e relações | N |
| 5 | Ler os dados do estudo | Literacia: causas múltiplas | E |
| 6 | Avaliar uma publicação numa rede social | Literacia: verdadeiro, falso ou simplificado | U |
| Final | Cadeado `BORNEU` e explicação final | Comparar com a hipótese inicial | — |

O progresso fica guardado no navegador de cada equipa. No fim, a equipa pode descarregar as respostas num ficheiro de texto ou imprimi-las.

## Fontes

Notícia adaptada de: "Your Halloween Candy Could Be Killing Orangutans", HuffPost, 18 de outubro de 2016. https://www.huffpost.com/entry/halloween-candy-orangutans-sustainable_n_5805cc1ee4b0b994d4c12ad5

Dados da sala 5:

Voigt, M., Wich, S. A., Ancrenaz, M., et al. (2018). Global demand for natural resources eliminated more than 100,000 Bornean orangutans. *Current Biology*, 28(5), 761–769.
