# Meu Bitcoin — site de lançamento

Site estático pronto para publicar no EasyPanel.

## Publicar

1. Envie todo o conteúdo desta pasta para um repositório Git.
2. No EasyPanel, crie um serviço **App** usando esse repositório.
3. Em **Build**, selecione **Dockerfile**.
4. Em **Domains**, aponte `meubitcoin.tech` para a porta `80`.
5. Faça o deploy.

O domínio deve ter um registro DNS `A` apontando para o IP público do servidor EasyPanel.
