# Exemplos para mostrar na TV

Páginas prontas para o instrutor mostrar que **dá para montar qualquer tipo de página** com HTML, CSS e um pouco de JavaScript. **Não são modelo para os alunos** e não seguem o padrão do `site-modelo/`. Tudo é inventado (sem nome, foto ou dado de ninguém), sem internet e sem nenhuma biblioteca: abre com dois cliques, direto do arquivo.

**Como usar:** no ar, em **https://medinagui.github.io/laboratorio-ams/exemplos/** (depois de publicar o laboratório). Sem internet, abra `laboratorio/exemplos/index.html` direto do arquivo (vai junto no pendrive do laboratório). A página inicial tem um cartão para cada exemplo. Em qualquer um, **Ctrl + U** mostra o código: "olha, é o mesmo tipo de texto que vocês estão escrevendo".

| Página | O que mostra | O que tem de novo no código |
|---|---|---|
| `cardapio.html` 🥟 | Cardápio de uma pastelaria | Grade de cartões (`display: grid`), preço em "pílula", selo "mais pedido" feito com `::after` |
| `festival.html` 🤖 | Página de um evento | Contagem regressiva ao vivo (**JavaScript**: `setInterval` a cada 1 s), robô dançando (`@keyframes`), fundo em degradê |
| `memoria.html` 🃏 | Jogo da memória com emojis | Um **jogo** de verdade em JavaScript: embaralha, vira as cartas, conta as jogadas |
| `galeria.html` 🎨 | Exposição de quadros | **Nenhuma imagem**: cada quadro é desenhado só com CSS (degradês, círculos, `clip-path`, animação) |
| `jornal.html` 📰 | Um jornal | Texto em colunas (`columns`), letra capitular, **tabela** (`<table>`, `<tr>`, `<td>`) |
| `tarefas.html` ✅ | Lista de tarefas | Um **aplicativo**: adiciona, marca e apaga tarefas, e guarda no navegador (`localStorage`) |

**Frases para puxar:**
- "Todas estas páginas usam as mesmas três coisas que o site de vocês: HTML (esqueleto), CSS (roupa) e, algumas, JavaScript (músculos)."
- No `galeria.html`: 🙋 *"Isso é uma foto?"* → não, é só CSS. Abra o Ctrl + U e mostre o `.planeta`.
- No `memoria.html`: "um jogo também é só uma página. Dá para publicar no GitHub Pages do mesmo jeito que o site de vocês."
- No `tarefas.html`: "ele lembra das tarefas mesmo fechando a página. É o mesmo truque que o laboratório usa para guardar o código."

Se alguém quiser o código de um exemplo: "Ctrl + U, copie e cole no laboratório". O resultado aparece, mas o JavaScript não roda lá (o laboratório só mostra HTML e CSS; ver `guia-estudo/05-laboratorio.md`).
