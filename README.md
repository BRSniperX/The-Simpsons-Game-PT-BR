<img width="1920" height="1080" alt="banner_1920x1080" src="https://github.com/user-attachments/assets/0bbb6c7e-242a-40b9-a0da-47a4b59ff040" />
# The Simpsons Game — Tradução PT-BR v1.1

Tradução de **The Simpsons Game** (Xbox 360) para português do Brasil, testada no emulador **Xenia Canary**.

## Novidades da v1.1

- **O aplicador aceita outros dumps do mesmo disco.** Antes ele exigia o ISO com SHA-1 idêntico ao usado na tradução, e dumps do mesmo jogo com o mesmo tamanho (como `Simpsons Game, The (USA).iso`) eram recusados. Agora ele confere só o que o jogo lê do disco: identificação, diretórios e o conteúdo de cada arquivo. A partição de vídeo e o preenchimento, que variam entre dumps, não importam mais. Se os dados do jogo forem diferentes, ele continua recusando.
- **18 falas de cenas que tinham ficado em inglês agora estão traduzidas**: museu do Bartman, O Dia em que Springfield Parou, Volta ao Mundo em 80 Mordidas e Abraçador de Árvores. Elas ficam guardadas num formato diferente do resto das falas e tinham escapado do instalador; uma varredura do disco inteiro confirmou que não sobrou nenhuma outra.

Já aplicou a v1.0? Aplique a v1.1 sobre o ISO **original**, não sobre o traduzido. Os saves continuam valendo.

## O que está traduzido

- Todos os menus, opções, avisos do sistema, tutoriais, objetivos e dicas
- Legendas de todas as cenas do jogo
- **7.403 falas de jogabilidade e de cena**: tudo o que os personagens dizem enquanto você joga, em todos os episódios e em Springfield
- Clichês de videogame, troféus, colecionáveis, bastidores (Making Of) e os cargos dos créditos
- As frases do Bart no quadro-negro da escola
- Mais de 9.500 linhas no total, revisadas em duas passadas, com nomes e bordões no estilo da dublagem brasileira da série; piadas e trocadilhos adaptados, sem censura

## Requisitos

| | |
|---|---|
| Jogo | **The Simpsons Game**, Xbox 360, versão **NTSC-U** (EUA) |
| Title ID | `45410809` |
| ISO | **completo**: 7.835.492.352 bytes (7.651.848 KB no Windows Explorer) |
| Sistema | Windows 10 ou 11, uns 8 GB livres no disco |
| Testado em | Xenia Canary |

> ⚠️ Não serve ISO reduzido (XISO / "trimmed"), nem versão PAL ou de outra região. O aplicador confere os dados do jogo antes de começar e recusa se não forem os certos.

## Instalação

1. Extraia `The-Simpsons-Game-PTBR-v1.1.zip` em qualquer lugar.
2. Coloque o ISO original do jogo dentro da pasta extraída (ou arraste o ISO em cima do `APLICAR_PATCH.bat`).
3. Dê dois cliques em **`APLICAR_PATCH.bat`**.
4. No fim aparece **`The Simpsons Game (PT-BR).iso`** ao lado do original. Abra esse arquivo no Xenia.

O aplicador usa só o PowerShell que já vem no Windows: não precisa instalar nada. Ele não altera o ISO original e confere o resultado no fim. Partindo do dump usado na tradução (SHA-1 `350610e489691e60687d4b2983bb6369350b38f4`), o resultado tem SHA-1 `2683bba97e11b9db456509c426e120d4f129722f`. Se o Windows mostrar "O Windows protegeu o computador", clique em *Mais informações → Executar assim mesmo*.

## Observações

- O áudio continua em inglês (o jogo não tem dublagem em português): ative as legendas nas opções.
- Placas, cartazes e letreiros do cenário e o logo do título ficam em inglês.
- 17 gritos de luta (do chefão "Sky Sumo" e do guarda Lou) ficam em inglês: o pacote onde eles estão trava o jogo se for alterado.
- Saves de antes da tradução continuam funcionando.

## Arquivos

| Arquivo | Para |
|---|---|
| `The-Simpsons-Game-PTBR-v1.1.zip` | aplicador + patch |
| `LEIA-ME.txt` | instruções completas |
| `SHA256SUMS.txt` | verificação: `sha256sum -c SHA256SUMS.txt` |

---

Tradução de fã por BRSniperX, gratuita e sem vínculo com a Electronic Arts nem com os detentores de *Os Simpsons*. É preciso ter o jogo original.
