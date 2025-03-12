# 📊 Cadastro de Nomes da Equipe Inimiga

Este programa permite que você registre rapidamente os campeões que a equipe inimiga está escolhendo durante a tela de **Picks e Bans**. Ele é rápido, simples de usar e mantém o registro salvo, mesmo se você fechar ou atualizar a página.

---

## 🚀 Como Usar o Programa

1. **Adicionar nomes rapidamente:**
   - Digite o nome do campeão no campo de entrada.
   - Pressione **Enter** ou clique no botão **Adicionar** para registrar o nome.
   
2. **Acompanhar os nomes adicionados:**
   - O programa exibe em tempo real o **Top 10 nomes mais inseridos**.
   - Cada vez que você adiciona um campeão, a contagem dele aumenta.

3. **Corrigir nomes digitados errado:**
   - Caso você insira um nome incorreto, clique no **ícone de lápis (✏️)** ao lado do nome.
   - Digite o nome correto e a contagem será transferida automaticamente.
   - Os dados atualizados ficam salvos no navegador.

---

## 📥 Exportar o Banco de Dados

Você pode **baixar todos os nomes cadastrados** em um arquivo `.json`, o que permite editar manualmente ou guardar os registros.

### Para exportar:
1. Clique no botão **"📥 Baixar Banco de Dados"**.
2. Um arquivo chamado `banco_de_nomes.json` será gerado automaticamente.

---

## ✏️ Editar Manualmente os Nomes

Se precisar corrigir vários nomes de uma vez ou fazer ajustes avançados:

1. Abra o arquivo `banco_de_nomes.json` em um editor de texto (ex.: **Bloco de Notas** ou **VS Code**).
2. O arquivo tem a seguinte estrutura:
   ```json
   {
      "Shaco": 12,
      "Ahri": 8,
      "Jinx": 5
   }
