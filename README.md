# Igreja Adventista do Sétimo Dia — Santa Isabel

Site institucional estático para GitHub Pages, com painel administrativo em `/admin`.

## 1. Configurar o repositório
1. Crie um repositório público chamado `igreja-santa-isabel` no GitHub.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Edite `assets/js/config.js`: preencha `owner` com seu usuário do GitHub e confirme `repo` e `branch`.
4. No repositório, acesse **Settings → Pages**.
5. Em **Build and deployment**, escolha **Deploy from a branch**, selecione `main` e `/ (root)`, e salve.

## 2. Usar o painel
Abra `https://SEU_USUARIO.github.io/igreja-santa-isabel/admin/`.

Para editar, crie um token Fine-grained em GitHub → Settings → Developer settings → Personal access tokens. Limite-o a este repositório e conceda **Contents: Read and write**. Use o token no painel. Ele é mantido apenas na sessão atual do navegador; não o coloque nos arquivos do site nem o compartilhe.

O painel permite alterar textos, programação, links sociais, link do mapa e enviar/remover fotos da galeria. Após salvar, aguarde alguns minutos para o GitHub Pages publicar a atualização.

## 3. Personalizar antes de publicar
- Troque `assets/uploads/capa.jpg` pela foto principal da igreja (mantenha exatamente esse nome).
- Atualize horários e links pelo painel.
- Para endereço, use um link de compartilhamento do Google Maps.
- Adicione a logo oficial quando estiver disponível.

## Observação de segurança
O site público não contém token. Cada administrador deve usar seu próprio token com acesso mínimo ao repositório e sair do painel ao terminar, especialmente em aparelhos compartilhados. O painel grava alterações diretamente no repositório GitHub.
