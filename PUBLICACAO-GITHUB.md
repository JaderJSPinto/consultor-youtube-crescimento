# Publicação deste projeto no GitHub

**Conta prevista:** `JaderJSPinto`  
**Repositório sugerido:** `consultor-youtube-crescimento`  
**Visibilidade solicitada:** **Public**

## Criar o repositório na interface do GitHub

1. Acesse https://github.com/new conectado à conta `JaderJSPinto`.
2. Em **Repository name**, informe `consultor-youtube-crescimento`.
3. Em **Description**, informe `Skill em português para planejar, criar, desenvolver e monetizar canais no YouTube com acompanhamento passo a passo.`
4. Escolha **Public**.
5. Deixe desmarcadas as opções que inicializam o repositório com README, `.gitignore` ou licença, pois os arquivos já estão preparados aqui.
6. Clique em **Create repository**.

## Enviar o conteúdo

### Alternativa A — interface do GitHub

1. Extraia o arquivo `github-consultor-youtube.zip` em seu computador.
2. No repositório vazio, use **uploading an existing file**.
3. Envie `README.md`, `PUBLICACAO-GITHUB.md`, `skill.zip` e a pasta `consultor-youtube-crescimento` com seus arquivos e subpastas. Caso o navegador não aceite pastas, use o método Git abaixo.
4. Confirme o commit com a mensagem `Publica Consultor YouTube e documentação em português`.
5. Confira se o README aparece na página principal e se `skill.zip` está disponível.

### Alternativa B — linha de comando Git

No terminal, dentro da pasta extraída (a que contém `README.md`):

```bash
git init
git branch -M main
git add .
git commit -m "Publica Consultor YouTube e documentacao"
git remote add origin https://github.com/JaderJSPinto/consultor-youtube-crescimento.git
git push -u origin main
```

O comando `git push` pede autenticação via método configurado para sua conta. Não insira senhas ou tokens em chats públicos.

## Verificação

Depois do envio, confira o endereço:

`https://github.com/JaderJSPinto/consultor-youtube-crescimento`

O repositório deve mostrar `Public`, o `README.md`, o arquivo `skill.zip` e a pasta de código-fonte da Skill.

A publicação no GitHub não instala automaticamente a Skill no ChatGPT. Consulte o README para instruções de importação.
