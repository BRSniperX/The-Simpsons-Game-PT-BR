<img width="1920" height="1080" alt="banner_1920x1080" src="https://github.com/user-attachments/assets/0bbb6c7e-242a-40b9-a0da-47a4b59ff040" />
# The Simpsons Game — Tradução PT-BR v1.2

Tradução de **The Simpsons Game** (Xbox 360) para português do Brasil, testada no emulador **Xenia Canary**.

## Novidades da v1.2

- **As últimas 17 falas em inglês agora estão traduzidas**: o guarda Lou na barreira de Springfield e o Cara dos Quadrinhos na luta "Sky Sumo". Elas ficam num pacote de personagens que travava o jogo quando era alterado; a investigação mostrou que o problema era o arquivo mudar de lugar no disco, e agora ele é gravado no lugar original. **Todas as falas do jogo estão em português.**

Na v1.1: o aplicador passou a aceitar qualquer dump completo NTSC-U do disco, e 18 falas de cenas foram traduzidas.

Já aplicou uma versão anterior? Apague ou renomeie o `The Simpsons Game (PT-BR).iso` antigo e aplique a v1.2 sobre o ISO **original**, não sobre o traduzido. Os saves continuam valendo.

## O que está traduzido

- Todos os menus, opções, avisos do sistema, tutoriais, objetivos e dicas
- Legendas de todas as cenas do jogo
- **Todas as 7.420 falas de jogabilidade e de cena**: tudo o que os personagens dizem enquanto você joga, em todos os episódios e em Springfield
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

1. Extraia `The-Simpsons-Game-PTBR-v1.2.zip` em qualquer lugar.
2. Coloque o ISO original do jogo dentro da pasta extraída (ou arraste o ISO em cima do `APLICAR_PATCH.bat`).
3. Dê dois cliques em **`APLICAR_PATCH.bat`**.
4. No fim aparece **`The Simpsons Game (PT-BR).iso`** ao lado do original. Abra esse arquivo no Xenia.

O aplicador usa só o PowerShell que já vem no Windows: não precisa instalar nada. Ele não altera o ISO original e confere o resultado no fim. Partindo do dump usado na tradução (SHA-1 `350610e489691e60687d4b2983bb6369350b38f4`), o resultado tem SHA-1 `9204c4bd2cb66ef56604611a5fa7e6096938c203`. Se o Windows mostrar "O Windows protegeu o computador", clique em *Mais informações → Executar assim mesmo*.

## Observações

- O áudio continua em inglês (o jogo não tem dublagem em português): ative as legendas nas opções.
- Placas, cartazes e letreiros do cenário e o logo do título ficam em inglês.
- Saves de antes da tradução continuam funcionando.

## Arquivos

| Arquivo | Para |
|---|---|
| `The-Simpsons-Game-PTBR-v1.2.zip` | aplicador + patch |
| `LEIA-ME.txt` | instruções completas |
| `SHA256SUMS.txt` | verificação: `sha256sum -c SHA256SUMS.txt` |

---

Tradução de fã, gratuita e sem vínculo com a Electronic Arts nem com os detentores de *Os Simpsons*. É preciso ter o jogo original.
