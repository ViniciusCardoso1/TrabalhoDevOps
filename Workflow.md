#  Workflow de Desenvolvimento - Guia da Vida Universitária

##  Modelo Adotado
- Uso do **GitHub Flow**, por ser simples e adequado para projetos pequenos.
- A branch `main` representa sempre o código estável.
- Novas alterações são feitas em branches específicas.
- Integração ocorre por meio de Pull Requests (PR), sempre revisados.

---

##  Estratégia de Branches
- `main` → branch estável do projeto (produção).
- `feature/nome-da-feature` → novas funcionalidades.
- `fix/nome-do-bug` → correções de erros.
- `docs/` → alterações de documentação.

**Convenção de nomes:**  
`tipo/nome-curto-descritivo` (ex: `feature/menu-responsivo`, `fix/imagem-quebrada`).

---

##  Regras de Atualização
- Sempre atualizar a branch `main` antes de iniciar uma nova tarefa.
- Branches devem ser pequenas e com commits frequentes.
- Alterações devem ser integradas apenas via Pull Request.
- Caso a branch fique desatualizada, deve ser sincronizada com a `main` antes do merge.
- Não é permitido commit direto na branch `main`.

---

##  Política de Revisão e Integração
- Todo Pull Request deve ser revisado por pelo menos **um membro do time**.
- Revisões devem avaliar:
  - Clareza e qualidade do código.
  - Estrutura correta de HTML e CSS.
  - Consistência nos nomes de arquivos, classes e commits.
- O merge só é permitido após aprovação.
- O histórico de commits deve ser limpo e seguir a padronização.

---

##  Padronização de Commits Semânticos
**Sintaxe:**
- `tipo(escopo opcional): descrição breve`

**Exemplos:**
- `feat(lazer): adicionar seção de eventos culturais`
- `fix(transporte): corrigir caminho da imagem do ônibus`
- `docs: atualizar README com instruções de instalação`

---

##  Tipos de Commit do Projeto
**Tipos já conhecidos:**
- `feat` → nova funcionalidade.  
- `fix` → correção de bug.  
- `docs` → documentação.  
- `style` → ajustes de formatação (espaços, identação, aspas etc.).  
- `refactor` → refatoração sem alterar funcionalidade.  
- `test` → criação ou ajuste de testes.  
- `chore` → tarefas de manutenção (configs, dependências etc.).

**Novos tipos criados para este projeto:**
- `content` → atualização de textos e imagens do guia.  
- `layout` → mudanças estruturais de HTML/CSS que afetam a disposição dos elementos.  
- `accessibility` → melhorias de acessibilidade (alt em imagens, contraste, navegação por teclado).  

---

##  Benefícios do Workflow
- Organização e rastreabilidade do código.  
- Maior qualidade e consistência nas entregas.  
- Histórico de commits claro e legível.  
- Facilidade para novos membros entenderem o fluxo do projeto.
