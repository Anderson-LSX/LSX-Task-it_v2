# T-000 – Passo Zero: Preparação do Projeto Organizador v2

## Objetivo
Preparar a fundação do projeto Organizador v2, garantindo:
- Estrutura física de pastas e arquivos
- Controle de versão local e remoto via Git
- Registro do Kanban físico e digital
- Preparação completa do ambiente de desenvolvimento
- Procedimentos rastreáveis e auditáveis

---

## 1️⃣ Preparação do Ambiente

- [x] VS Code ou outro editor de código
- [x] Navegador de internet 
- [ ] Git instalado e funcional
- [x] PHP instalado 

---

## 2️⃣ Estrutura Física do Projeto
- [x] Criar pasta principal: `Organizador_v2`
- [x] Criar subpastas:
  - [x] `config/`
  - [x] `controllers/`
  - [x] `models/`
  - [x] `views/`
  - [x] `public/`
  - [x] `docs/`
    - [x] `components/`
    - [x] `kanban/`
- [x] Criar arquivo Markdown do Kanban físico: `docs/kanban.md`
  
  ```markdown
  | 🧰 A Fazer | ⚙️ Em Progresso | ✅ Concluído |
  |------------|-----------------|--------------|
  | Preparar ambiente e Kanban físico | | ✅ |
  ```
- [x] Criar arquivo de documentação T-000: `docs/T-000_Passo_Zero.md`

---

## 3️⃣ Inicializar Git Local
- [ ] Abrir painel Source Control no VS Code ou terminal
- [ ] Inicializar repositório: `git init`
- [ ] Adicionar arquivos: `git add .`
- [ ] Criar commit inicial:
```
git commit -m "docs(T-000): estrutura inicial e Kanban físico"
```
- [ ] Criar branch de desenvolvimento: `git checkout -b dev`
- [ ] Confirmar branch ativa: `git branch`

---

## 4️⃣ Gerar Personal Access Token (PAT) no GitHub
- [ ] Acessar: [https://github.com/settings/tokens](https://github.com/settings/tokens)
- [ ] Clique em **Generate new token → Tokens (classic)**
- [ ] Configurar:
  - Nome: `Organizador_v2 CMD`
  - Expiração: 90 dias (ou conforme política)
  - Permissões: `repo` (push/pull)
- [ ] Copiar token e armazenar em local seguro
- [ ] Usar PAT como **senha** ao fazer push/pull via HTTPS

---

## 5️⃣ Configurar Repositório Remoto
- [ ] Adicionar remoto:
```
git remote add origin https://github.com/Anderson-LSX/LSX-Task-it_v2.git
```
- [ ] Verificar remoto: `git remote -v`

---

## 6️⃣ Push Inicial para GitHub
- [ ] Enviar branch `dev` para GitHub:
```
git push -u origin dev
```
- [ ] Inserir:
  - Usuário GitHub: `Anderson-LSX`
  - Senha: **PAT gerado**
- [ ] Confirmar commit inicial (T-000) no repositório remoto

---

## 7️⃣ Configurar Kanban Digital no GitHub
- [ ] Acessar aba **Projects** do repositório
- [ ] Criar novo **Board Kanban**
- [ ] Criar colunas:
  - Backlog
  - Planejamento
  - Em Desenvolvimento
  - Em Testes
  - Concluído
- [ ] Criar cartão **T-000**, vincular ao commit inicial

---

## Resultados Esperados
- Estrutura física do projeto pronta
- Kanban físico registrado
- Repositório Git local e remoto configurado
- Branch `dev` criada e commit inicial registrado
- PAT gerado e usado corretamente
- Kanban digital configurado e T-000 vinculado ao commit

---

## Observações e Boas Práticas
- Cada checkbox deve ser marcado conforme o passo for concluído
- Todo o procedimento é rastreável para auditoria
- Este documento serve de base para todos os próximos passos do projeto (T-001, T-002, …)

> **Observação de Sincronização:**  
> Sempre que uma alteração for feita no Kanban digital (mudança de coluna, checklist ou descrição), lembre-se de atualizar o arquivo `.md` correspondente para manter a documentação oficial sincronizada.

### Histórico de Atualizações
- [x] 2025-10-29 — Criados arquivos `template_cartao.md` e `guia_kanban.md` (ver T-001)
