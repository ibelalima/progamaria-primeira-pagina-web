# Skill: Automatizador de Mensagens de Commit

## Objetivo
Criar mensagens de commit claras, consistentes e automáticas para facilitar o histórico de versão do projeto.

## Como usar
1. Identifique o tipo de alteração:
   - `feat`: nova funcionalidade
   - `fix`: correção de bug
   - `refactor`: refatoração de código
   - `docs`: documentação
   - `style`: ajustes de estilo/formatacao
   - `chore`: tarefas de manutenção
2. Escreva uma descrição curta e objetiva no infinitivo.
3. Se necessário, adicione um corpo explicando o motivo.

## Template
```text
<tipo>(<escopo opcional>): descrição curta em português

Corpo opcional com mais detalhes e motivo da mudança.
```

## Exemplos
- `feat: adicionar seção de contato com formulário responsivo`
- `fix: corrigir link quebrado do botão de cadastro`
- `refactor: organizar classes CSS do cabeçalho`
- `docs: atualizar instruções de uso no README`
- `style: ajustar espaçamento dos cards no mobile`
- `chore: atualizar dependências e limpar CSS não utilizado`

## Prompt para IA / Copilot
Use este modelo para gerar mensagens de commit automaticamente:

```text
Gere uma mensagem de commit em português, no formato convencional, descrevendo as alterações abaixo. Seja curto, use tipo e escopo quando fizer sentido.

Alterações:
- [descreva aqui o que foi alterado]
```

### Exemplo de prompt preenchido
```text
Gere uma mensagem de commit em português, no formato convencional, descrevendo as alterações abaixo. Seja curto, use tipo e escopo quando fizer sentido.

Alterações:
- adição de menu mobile responsivo
- correção de borda do botão principal
```

Saída esperada:
`feat(menu): adicionar menu mobile responsivo e corrigir borda do botão principal`

## Dicas
- Sempre comece com o tipo e, quando possível, inclua o escopo entre parênteses.
- Use verbo no infinitivo: `adicionar`, `corrigir`, `atualizar`, `remover`.
- Mantenha a linha de commit principal com até 50 caracteres.
- Se precisar, adicione um corpo com o "por quê" da mudança.
