# Como usar o ODuo Studio (VS Code)

Seu workspace de conteúdo: markdown com preview ao vivo, as diretrizes à mão e um seletor de fase.

## 1. Preview ao vivo (o "como vai ficar")
Abra qualquer arquivo `.md` e tecle **`Ctrl+K`** e depois **`V`** → abre o preview **lado a lado**, que atualiza enquanto você digita. (Tela cheia: **`Ctrl+Shift+V`**.)

## 2. Instale os 2 complementos sugeridos
Ao abrir esta pasta, o VS Code mostra um aviso no canto inferior direito ("Esta pasta recomenda extensões") → **Install**. Eles dão um preview melhor e **renderizam os diagramas** (mermaid) do [FLUXOGRAMA.md](FLUXOGRAMA.md).

## 3. Veja e troque a fase — o seu seletor
[ESTADO.md](ESTADO.md) é o painel. Lá você vê a **fase atual** e o **foco do mês**. Para trocar de fase, siga o passo a passo no fim do arquivo (mover o ▶, marcar `[x]`, atualizar o foco).

## 4. Comece um conteúdo (com os atalhos)
Crie um arquivo novo (ex.: `Producao/2026-06.md`). Digite um atalho e aperte **`Tab`**:

| Atalho | O que insere |
|---|---|
| `!sessao` | cabeçalho de sessão — **escolhe a ferramenta e a fase num dropdown** |
| `!fase1` `!fase2` `!fase3` | o bloco de contexto daquela fase |
| `!contrato1` | molde do plano (Cartógrafo) |
| `!contrato2` | molde do calendário/sequência (Arquiteto) |
| `!contrato3` | molde do post (Forja) |

> Onde tem dropdown (ex.: ferramenta, fase, formato), use as **setas ↑↓** e **`Enter`** para escolher, depois `Tab` para o próximo campo.

## 5. As 5 ferramentas
Os manuais estão na tabela do [ESTADO.md](ESTADO.md). O fluxo de cada uma está no [FLUXOGRAMA.md](FLUXOGRAMA.md).

## 6. Rodar a IA
A integração com IA ficou para um segundo momento (você decide o caminho). Por enquanto o fluxo é: abra o **manual da ferramenta** de um lado e o seu **rascunho** do outro, e siga o processo do manual.

---

### Sugestão de organização (opcional)
Pastas para não misturar: `Producao/` (rascunhos do mês), `Inspiracao/` (garimpos), `Arquivo/` (o que já saiu). As diretrizes e os manuais ficam na raiz.
