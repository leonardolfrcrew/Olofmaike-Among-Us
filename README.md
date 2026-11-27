# Olofmaike Among Us

Repositório privado do projeto para Among Us no Windows. A edição offline se destina a testes locais no modo Treino.

## Status da edição offline

Ainda não há uma versão offline disponível neste repositório. Quando houver um pacote, a página de [Releases](../../releases) deverá informar a versão do jogo testada, a loja compatível e as dependências. O procedimento de instalação depende dessas informações.

## Antes de testar uma edição offline

1. Abra o jogo original e confirme que o modo Treino carrega normalmente.
2. Compare a versão exibida no menu principal com a versão indicada na release.
3. Feche o jogo e mantenha uma cópia limpa da instalação. Use uma pasta separada para testar o mod.
4. Siga as instruções da release correspondente e faça o primeiro teste no modo Treino.

## Como restaurar a instalação original

1. Feche o jogo. Se você usou uma pasta separada para o mod, abra o jogo pela instalação original na biblioteca da loja.
2. Se a instalação da biblioteca foi modificada, mova para uma pasta de backup os arquivos adicionados pelo mod. Em instalações com BepInEx, confira se a pasta `BepInEx` e o arquivo `winhttp.dll` vieram do pacote antes de movê-los. A verificação da loja pode deixar arquivos extras na pasta.
3. Na Epic Games, abra a Biblioteca, selecione os três pontos ao lado de Among Us e use **Gerenciar → Verificar**. No Steam, abra **Propriedades → Arquivos instalados → Verificar integridade dos arquivos**.
4. Inicie o jogo pela biblioteca e confirme que o menu principal e o modo Treino carregam.

## Como relatar um problema

Abra uma [issue](../../issues) com a versão do jogo, a loja, a versão do pacote, o comportamento esperado e os passos para reproduzir o problema no modo Treino. Revise os logs antes de anexá-los e remova caminhos pessoais, identificadores e credenciais.
