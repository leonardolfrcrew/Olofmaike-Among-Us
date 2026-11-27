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

## Como encontrar a pasta do jogo

- **Epic Games** — na Biblioteca, abra o menu de três pontos de Among Us e selecione **Gerenciar**. Veja o local da instalação e abra essa pasta no Explorador de Arquivos.
- **Steam** — na Biblioteca, clique com o botão direito em Among Us e escolha **Gerenciar → Explorar arquivos locais**.
- Confirme que a pasta aberta contém `Among Us.exe`. Antes de qualquer teste, feche o jogo e preserve a instalação da biblioteca como referência.

## Checklist de teste no modo Treino

| Verificação | Resultado esperado |
| --- | --- |
| Abrir a cópia original | O jogo chega ao menu principal. |
| Anotar a versão do jogo e a loja | Os dados podem ser comparados com a página da release. |
| Entrar no Treino | O mapa carrega e o personagem responde aos controles. |
| Fazer uma tarefa e voltar ao menu | A tarefa funciona e o jogo retorna ao menu sem fechar. |
| Repetir na edição offline, quando disponível | O resultado pode ser comparado com a cópia original. |

## Solução de problemas

| Sintoma | O que verificar |
| --- | --- |
| O jogo fecha antes de chegar ao menu | Abra a instalação original pela biblioteca. Se ela também falhar, faça a verificação de arquivos na loja e tente novamente. |
| O jogo abre, mas o Treino fica travado | Repita o teste na cópia original e anote em qual tela o problema começa. |
| O jogo continua modificado depois de verificar os arquivos | Confirme que o atalho abre a pasta da biblioteca. Compare os arquivos extras com o conteúdo do pacote instalado e mova apenas os arquivos identificados para uma pasta de backup. |
| O jogo foi atualizado pela loja | Anote o novo número de versão. Antes de retomar os testes, confira se a release declara compatibilidade com essa versão. |

## Informações esperadas de uma release offline

Uma release precisa identificar a versão do pacote, a versão do jogo testada, a loja compatível, as dependências e seus números de versão, os arquivos que serão adicionados e os passos para instalação e remoção. O ZIP da release deve ter um nome com versão e um hash SHA-256 publicado para conferência.

No PowerShell, para conferir o SHA-256 de um pacote futuro, execute o comando abaixo com o caminho do arquivo e compare o resultado com o hash da release.

```powershell
Get-FileHash -LiteralPath 'C:\caminho\pacote-offline.zip' -Algorithm SHA256
```

## Modelo de relato de problema

- Versão do jogo e loja
- Versão do pacote, se aplicável
- Mapa do modo Treino e tarefa testada
- Passos para reproduzir
- Resultado esperado e resultado observado
- Resultado na instalação original
- Trecho relevante do log, se houver
