# Como criar uma nova branch no Git

Para criar uma nova branch no Git, siga os passos abaixo:

1. **Verifique a branch atual**:
    ```bash
    git branch
    ```
    Isso mostrará todas as branches locais e indicará em qual você está atualmente.

2. **Crie uma nova branch**:
    ```bash
    git branch nome-da-nova-branch
    ```
    Substitua `nome-da-nova-branch` pelo nome desejado para a nova branch.

3. **Mude para a nova branch**:
    ```bash
    git checkout nome-da-nova-branch
    ```
    Isso mudará o seu repositório para a nova branch que você acabou de criar.

4. **Verifique novamente a branch atual**:
    ```bash
    git branch
    ```
    Agora, a nova branch deve estar marcada com um asterisco (*), indicando que você está nela.

## Comandos combinados

Você também pode criar e mudar para a nova branch com um único comando:
```bash
git checkout -b nome-da-nova-branch
```

Isso cria a nova branch e muda para ela imediatamente.

## Confirmando a criação da branch

Para confirmar que a nova branch foi criada e que você está nela, use:
```bash
git status
```
Isso mostrará o status do repositório na nova branch.

Pronto! Agora você sabe como criar e mudar para uma nova branch no Git.