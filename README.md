# GitHub Copilot

## Criando e Publicando uma Nova Branch no Git

Para criar e publicar uma nova branch no Git, siga os passos abaixo:

1. **Criar uma nova branch localmente**:
   ```bash
   git checkout -b nome-da-branch
   ```
   Substitua `nome-da-branch` pelo nome desejado para sua branch.

2. **Fazer alterações e commit**:
   Após realizar as alterações necessárias nos arquivos, adicione e faça o commit:
   ```bash
   git add .
   git commit -m "Descrição das alterações"
   ```

3. **Publicar a branch no repositório remoto**:
   Envie a nova branch para o repositório remoto:
   ```bash
   git push -u origin nome-da-branch
   ```

Agora sua branch está publicada e pronta para colaboração ou criação de um pull request.

> **Dica:** Use nomes de branch descritivos e consistentes para facilitar o entendimento do propósito da branch.
