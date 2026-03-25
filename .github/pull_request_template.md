# Descrição

Inclua um resumo da alteração e qual problema foi corrigido. Inclua também motivação e contexto relevantes. Liste todas as dependências necessárias para essa alteração. Você também adicionar o link da tarefa que você está trabalhando para referenciar o contexto/requisitos.

O título do PR deve conter a(s) chave(s) da tarefa no JIRA:

Exemplo: [PRT-556] Alteração nos campos do grid do painel de lista de preço 

### Tarefa no JIRA

- Key: PRT-556
- Link: https://redeancora.atlassian.net/browse/PRT-556

### Tipo de alteração

- [ ] Correção de bug (mudança ininterrupta que corrige um problema)
- [ ] Novo recurso (mudança ininterrupta que adiciona funcionalidade)
- [ ] Mudança de última hora (correção ou recurso que faria com que a funcionalidade existente não funcionasse conforme o esperado)
- [ ] Esta alteração requer uma atualização da documentação

### Como isso foi testado?

Forneça instruções para que possamos reproduzir. Liste também todos os detalhes relevantes para sua configuração de testes.

Deve haver ao menos um teste implementado que cobre essa mudança. Caso já não exista um (ou alguns), crie!

Liste aqui os testes implementados.

Caso ache pertinente, descreva os testes que você executou para verificar suas alterações.

Um exemplo: 

**Pré requisitos de Teste**: (remova caso seja necessário)
* Seed para entidade Product: novo dataset Products gerado.
* Redis v6.0.5: instalado e configurado. (caso não seja o já usado no docker do projeto)
