# Servidor de Atualizações - Priston Tale

Repositório público responsável pela distribuição automática de patches e arquivos do cliente de jogo através do **Launcher.exe**.

### Como atualizar o jogo para os jogadores:
1. Adicione os arquivos novos dentro da pasta `patch_files/`.
2. Adicione os arquivos no manifesto `patch.json` com o respectivo hash MD5.
3. Dê `git commit` e `git push`.
4. Todos os jogadores receberão os novos arquivos automaticamente ao abrir o Launcher.
