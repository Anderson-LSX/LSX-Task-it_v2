# 🗂️ Guia de Uso do Kanban Físico - Projeto Organizador v2

## Objetivo
Este guia explica como registrar tarefas, atualizar checklists e vincular tarefas do Kanban físico ao Kanban digital e commits no GitHub.

---

## Estrutura do Kanban Físico

### Categorias
- 📄 Documentação
- 🧠 Planejamento
- ⚙️ Desenvolvimento
- ✅ Testes / Validação

### Colunas
| 🧰 A Fazer | ⚙️ Em Progresso | ✅ Concluído |
|------------|-----------------|--------------|
| Tarefas pendentes | Tarefas em desenvolvimento | Tarefas finalizadas |

---

## Como utilizar

1. **Registrar nova tarefa**
   - Crie um cartão físico ou um novo item no `kanban.md`.
   - Use o modelo do `template_cartao.md`.
   - Dê um código único (ex: T-001, T-002, …).

2. **Atualizar checklist**
   - Marque `[x]` quando uma etapa for concluída.
   - Sempre sincronize as alterações no arquivo `.md` e no Kanban digital.

3. **Vincular commits**
   - Ao realizar um commit relacionado à tarefa:
     - Use `refs #XX` na mensagem para vincular à Issue.
     - Ou cole o link do commit na seção “Referências” do cartão.

4. **Atualizar status**
   - Movimente o cartão nas colunas (`A Fazer` → `Em Progresso` → `Concluído`) conforme o andamento da tarefa.
   - Atualize o Kanban digital simultaneamente para manter rastreabilidade.

---

## Boas práticas

- Sempre manter o Kanban físico e digital **sincronizados**.
- Use **nomes claros e objetivos** nos cartões.
- Mantenha os **checklists detalhados** para cada tarefa.
- Vincule sempre **commits e Issues** à tarefa correspondente.
