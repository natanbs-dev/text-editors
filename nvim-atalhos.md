## Básico do nvim:

- **BUSCAR(find): `/`**
    - **PROXIMO RESULTADO:`n`**
    - **RESULTADO ANTERIOR: `N`**
- **COPIAR CONTEUDO= `y`**
- **COLAR CONTEUDO: `p`**
- **DESFAZER: `u`**
- **CORTAR: `x`**
- **APAGAR: `d`**

---

## Explorar qualquer diretório:

- **EXPLORAR ARQUIVO OU PASTA EM TODO O PC:** `:e`

- **Abre explorador no diretório do arquivo atual (tipo o `ranger`):** `:Ex`

---

## Explorador de arquivos:

- **EXPLORADOR DE ARQUIVOS**: `SPACE + E`
- **CRIAR ARQUIVO:** `a` (porém finalizando com '/', cria-se pastas: ex:kernels/)
- **DELETAR ARQUIVOS:** `d`
- **MOVER ARQUIVOS**: `m`
- **COPIAR ARQUIVOS**: `y`
- **COLAR CONTEUDO**: `p`

---

## Divisão de janelas:

- **DIVIDIR VERTICALMENTE**: `SPACE + |`
- **DIVIDIR HORIZONTAL**: `SPACE + -`
- **FECHAR SLIT ATUAL: `:q`**
- **NAVEGAR ENTRE SPLITS: `Ctrl + h/j/k/l`**
    - **SPLIT DA DIREITA: `Ctrl + l`**
    - **SPLIT DA ESQUERDA: `Ctrl + h`**
    - **SPLIT DE BAIXO: `Ctrl + j`**
    - **SPLIT DE CIMA: `Ctrl + k`**
- **SELECIONAR A ABA (buffer) DA DIREITA: `L`**
- **SELECIONAR A ABA (buffer) DA ESQUERDA: `H`**

---

## SALVAR CONTEUDO E METODO DE SAIR

- **SALVAR ARQUIVO:** `:w`
- **SAIR SEM SALVAR:** `:q!`
- **SALVAR E SAIR:** `:wq`
- **FORÇAR SAIDA TOTAL:** `:qa!`

--- 

**Sobre criar pasta** — no Neo-tree (aberto com `Space + e`), pressione `a` e termine o nome com `/`. Por exemplo: `components/` cria uma pasta. Sem a barra, cria um arquivo.

**Sobre seleção** — o Vim não usa Shift para selecionar. O equivalente é entrar no modo Visual com `v` e mover o cursor normalmente com `h/j/k/l`, `w`, `b`, `$`, etc. A seleção acompanha o movimento. Para selecionar linhas inteiras use `V` (V maiúsculo).
