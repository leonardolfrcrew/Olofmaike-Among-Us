<div align="center">

# 🛸 Olofmaike Among Us (`OlofmaikesMenu`)

**Mod Menu completo e edição customizada para Among Us (Windows) com suporte a partidas Online e Offline.**

[![Versão do Mod](https://img.shields.io/badge/Versão-3.3.1-blue?style=for-the-badge)]()
[![Versão do Jogo](https://img.shields.io/badge/Among%20Us-2026.9.29-red?style=for-the-badge)]()
[![Plataforma](https://img.shields.io/badge/Plataforma-Windows%20(BepInEx%20IL2CPP)-0078D6?style=for-the-badge&logo=windows&logoColor=white)]()
[![Modos](https://img.shields.io/badge/Modos-Online%20%26%20Offline-brightgreen?style=for-the-badge)]()

[📥 Baixar Última Release](../../releases) • [🚀 Instalação](#-instalação-rápida) • [✨ Lista Completa de Funções](#-funcionalidades-do-mod) • [🛠️ Solução de Problemas](#️-solução-de-problemas)

</div>

---

## 📋 Sobre o Projeto

O **Olofmaike Among Us** (`OlofmaikesMenu v3.3.1`) é um mod menu avançado desenvolvido em C# sobre a arquitetura **BepInEx Unity IL2CPP** e **Harmony**, com suporte completo para partidas **Online** (salas públicas e privadas), **Multijogador Local (LAN)** e **Treino Offline (Freeplay)**.

A instalação é direta (**arrastar e soltar**): basta extrair os arquivos da release e jogá-los dentro da pasta raiz onde o seu *Among Us* está instalado.

> **Tecla padrão para abrir/fechar o menu:** `Delete` (configurável no arquivo de configuração ou perfil).

---

## 🎮 Compatibilidade

| Modo / Requisito | Status | Detalhes |
| :--- | :---: | :--- |
| **Versão Suportada do Among Us** | ✅ `2026.9.29` | O mod verifica a versão do jogo na inicialização para evitar falhas. |
| **Online (Sala Privada)** | ✅ Funcional | Compatível com recursos gerais e recursos exclusivos de Host. |
| **Online (Sala Pública)** | ✅ Funcional | Inclui proteções de privacidade (Spoofing de Plataforma, Nível e DeviceID). |
| **Multijogador Local (LAN)** | ✅ Funcional | Funciona normalmente em rede local. |
| **Treino Offline (Freeplay)** | ✅ Funcional | Todas as ferramentas de mapa, tarefas, funções e movimentação ativas. |

---

## 🚀 Instalação Rápida

1. **Feche o Among Us** caso esteja aberto.
2. Baixe o arquivo `.zip` mais recente na aba de [Releases](../../releases) e **extraia** todo o conteúdo.
3. Abra a pasta raiz de instalação do seu **Among Us** (onde fica o arquivo `Among Us.exe`).
4. **Pegue todos os arquivos e pastas extraídos e jogue/cole diretamente dentro da pasta do Among Us.**
   * *Se o Windows perguntar se deseja substituir arquivos, clique em **Substituir**.*
5. Inicie o jogo normalmente pela **Steam** ou **Epic Games**. A primeira abertura pode levar alguns segundos extras enquanto o BepInEx inicializa os plugins.

### 📂 Onde fica a pasta do jogo?
* **Steam:** Biblioteca → Clique com o botão direito em **Among Us** → **Gerenciar** → **Explorar arquivos locais**.
* **Epic Games:** Biblioteca → Clique nos **três pontos (`...`)** em **Among Us** → **Gerenciar** → Ícone de **pasta** ao lado de *Instalação*.

---

## ✨ Funcionalidades do Mod

Abaixo está a lista completa de todas as abas e funções presentes no **OlofmaikesMenu v3.3.1**:

### 👁️ 1. ESP & Visão (`ESPTab`)
* **See Player Info:** Exibe informações detalhadas dos jogadores (plataforma, nível, etc.).
* **See Roles:** Mostra o papel real de todos os jogadores da partida (Impostor, Tripulante, Engenheiro, Metamorfo, Fantasma, Detetive, Víbora, etc.).
* **See Ghosts:** Permite enxergar jogadores mortos (fantasmas) mesmo estando vivo.
* **See Lobby Info:** Exibe informações avançadas das salas no menu de matchmaking e lobbies.
* **No Shadows:** Remove completamente a névoa de guerra e sombras do mapa (Fullbright).
* **Task Arrows:** Mostra setas indicativas apontando para os objetivos das suas tarefas.
* **Reveal Votes:** Revela em quem cada jogador votou durante as reuniões (mesmo com votos anônimos ativados).
* **Nametags Customizadas:** Exibição aprimorada de nomes no mapa, nas reuniões e no chat.
* **Tracers (Linhas Guia):**
  * Rastreamento visual para **Tripulantes**, **Impostores**, **Fantasmas** e **Corpos Mortos**.
  * Modos de cor: **Color-based** (cor do jogador) ou **Distance-based** (muda de cor conforme a distância).
* **Minimap (Radar):**
  * Exibe a posição em tempo real de **Tripulantes**, **Impostores** e **Fantasmas** diretamente no minimapa, com opção de cores por jogador.
* **Câmera:**
  * **Zoom Out:** Afasta a câmera usando o scroll do mouse para enxergar grande parte do mapa.
  * **Freecam:** Câmera livre para explorar o mapa independentemente da posição do seu personagem.
  * **Spectate:** Menu dedicado para observar qualquer jogador da partida em tempo real.

---

### 🎭 2. Papéis & Habilidades (`RolesTab` & `RolesUI`)
* **Force Role (Host):** Menu para escolher e forçar qual papel cada jogador receberá no início da próxima partida (*Crewmate, Impostor, Engineer, Scientist, Tracker, Noisemaker, Guardian Angel, Shapeshifter, Phantom, Viper, Detective, Judge, Influencer*).
* **Set Fake Role:** Altera visualmente o seu papel localmente para testar interfaces e habilidades.
* **Set Fake Alive:** Permite simular o estado de "Vivo" ou "Morto" localmente.
* **Impostor & Metamorfo (Shapeshifter):**
  * **Kill Reach:** Aumenta o alcance do botão de eliminação.
  * **No Ss Animation:** Remove a animação de transformação do Metamorfo.
  * **Endless Ss Duration:** Duração infinita da transformação de Metamorfo.
* **Engenheiro (Engineer):**
  * **Endless Vent Time:** Tempo ilimitado dentro das tubulações (vents).
  * **No Vent Cooldown:** Zera o tempo de recarga para entrar nos dutos.
* **Rastreador (Tracker):**
  * **Endless Tracking:** Rastreamento contínuo sem expirar.
  * **No Track Delay / No Track Cooldown / Track Reach:** Remove atrasos, zera o cooldown e aumenta o alcance de rastreamento.
* **Cientista (Scientist):**
  * **Endless Battery:** Bateria infinita no painel portátil de sinais vitais (Vitals).
  * **No Vitals Cooldown:** Zera a recarga do painel de sinais vitais.
* **Detetive (Detective):**
  * **Interrogate Reach:** Aumenta o alcance da habilidade de interrogatório.

---

### 👑 3. Comandos Exclusivos de Host (`HostOnlyTab` & `ProtectUI`)
* **Murder (Eliminação Direta):**
  * **Kill Player / Telekill Player:** Menu de seleção rápida para eliminar um jogador específico à distância ou teleportando até ele.
  * **Kill All Crewmates / Kill All Impostors / Kill Everyone:** Elimina instantaneamente grupos inteiros ou todos os jogadores da partida.
  * **Kill Anyone / Kill While Vanished:** Permite eliminar qualquer alvo (incluindo outros impostores) e atacar mesmo estando invisível (*Phantom*).
  * **No Kill Cooldown:** Zera o tempo de recarga entre eliminações.
* **Game State & Reuniões:**
  * **Force Start Game:** Inicia a partida imediatamente no lobby sem aguardar contagem.
  * **No Game End:** Impede que a partida termine por critérios comuns de vitória/derrota.
  * **Skip Meeting:** Pula a reunião atual instantaneamente.
  * **Vote Immune:** Torna você imune a ser ejetado por votos.
  * **Eject Player:** Menu para ejetar qualquer jogador específico durante uma reunião.
* **Protect Menu (Proteção de Anjo da Guarda):**
  * Interface dedicada para aplicar escudo protetor em jogadores individuais (**Protect**), manter proteção contínua (**Keep Protected**) ou proteger toda a sala (**Protect Everyone / Keep Everyone Protected**).

---

### 🏃 4. Movimentação & Teleporte (`MovementTab`)
* **NoClip:** Permite atravessar paredes, portas e obstáculos livremente.
* **Invert Controls:** Inverte os controles de direção do personagem.
* **Speed & Ghost Speed:** Controle deslizante (slider) para ajustar livremente a velocidade de movimento vivo ou como fantasma.
* **Teleport:**
  * **Teleport to Cursor:** Teleporta seu personagem para a posição exata do cursor do mouse.
  * **Teleport to Player:** Menu para teleportar instantaneamente até qualquer jogador da sala.

---

### 🚢 5. Nave, Sabotagens & Portas (`ShipTab` & `DoorsUI`)
* **Sabotagens Rápidas:**
  * Ativação direta de **Reator (Reactor)**, **Oxigênio (Oxygen)**, **Luzes (Lights)**, **Comunicações (Comms)**, **Mushroom Mixup** e **Trigger Spores** (mapa *The Fungle*).
  * **Open Sabotage Map:** Abre o mapa de sabotagens a qualquer momento.
  * **Unfixable Lights:** Impede que os jogadores consertem a sabotagem das luzes.
* **Controle de Portas (`DoorsUI`):**
  * Menu separado por salas do mapa com status em tempo real (**Open**, **Closed**, **Mixed**).
  * Ações por sala ou globais: **Close**, **Open**, **Spam Close**, **Spam Open**, **Close All**, **Open All**, **Spam Close All**, **Spam Open All**.
  * **Auto-Open Doors On Use:** Abre automaticamente portas trancadas ao interagir com elas.
* **Tubulações (Vents) & Reuniões:**
  * **Use Vent / Walk In Vents:** Permite usar dutos com qualquer papel e andar livremente enquanto estiver dentro da rede de ventilação.
  * **Unlock Vents / Kick All From Vents:** Destranca dutos bloqueados e expulsa todos os jogadores escondidos nas tubulações.
  * **Call Meeting / Close Meeting:** Convoca ou encerra reuniões de emergência remotamente.
  * **Auto-Report Dead Bodies:** Reporta corpos automaticamente ao passar perto deles.

---

### ✅ 6. Tarefas (`TasksTab` & `TasksUI`)
* **Complete My Tasks:** Conclui instantaneamente todas as suas tarefas pendentes.
* **Tasks Menu (`TasksUI`):** Lista detalhada das suas tarefas atuais com acompanhamento de progresso e opção de completar tarefas individualmente.

---

### 🎬 7. Animações Visuais (`AnimationsTab`)
* Força a reprodução das animações visuais do personagem para todos verem (com opção **Client-Sided** para rodar apenas na sua tela):
  * **Shields** (Escudos)
  * **Asteroids** (Armas / Asteroides)
  * **Empty Garbage** (Esvaziar Lixo)
  * **Medbay Scan** (Scanner da Enfermaria)
  * **Cams In Use** (Luz vermelha das câmeras ativada)
  * **Moonwalk** (Andar de costas)

---

### 💬 8. Chat & Caixa de Texto (`ChatTab`)
* **Enable Chat:** Habilita o chat mesmo durante momentos em que ele fica bloqueado.
* **Bypass URL Block:** Permite enviar links e e-mails no chat sem serem censurados pelo filtro do jogo.
* **Lower Rate Limits:** Reduz o bloqueio de anti-spam para enviar mensagens mais rápido.
* **Unlock Extra Characters:** Libera símbolos e caracteres especiais bloqueados na caixa de texto.
* **Allow Longer Messages:** Aumenta o limite máximo de caracteres por mensagem.
* **Unlock Clipboard:** Permite usar `Ctrl + C` e `Ctrl + V` livremente no chat.

---

### 🛡️ 9. Passivo, Privacidade & Spoofing (`PassiveTab` & Configs)
* **Free Cosmetics:** Desbloqueia gratuitamente chapéus, skins, visores, pets e placas de identificação.
* **Avoid Penalties:** Evita penalidades de tempo por desconexão/abandono de partidas.
* **Unlock Extra Features:** Libera recursos restritos de conta (como Freechat, Lista de Amigos e Nome Customizado).
* **Copy Lobby Code on Disconnect:** Copia automaticamente o código da sala para a área de transferência caso você seja desconectado.
* **Spoofing & Privacidade (Configurável via BepInEx):**
  * **Spoof Platform:** Altera a plataforma exibida para outros jogadores (*Steam, Epic Games, Android, iOS, Nintendo Switch, PlayStation, Xbox, etc.*).
  * **Spoof Level:** Personaliza o nível exibido (entre `1` e `100001`).
  * **Spoof Date to April 1st:** Ativa o modo visual de 1º de Abril (inversão de mapas/chapéus).
  * **Hide DeviceId:** Mascara o identificador único de hardware do dispositivo.
  * **No Telemetry:** Bloqueia o envio de dados analíticos e telemetria para os servidores da Unity/Innersloth.

---

### ⚡ 10. Overload & Stress Test (`OverloadTab` & `OverloadUI`)
* Ferramenta avançada de envio de pacotes RPC para testes de rede/servidor com:
  * Seleção de alvos individuais ou em massa (**All**, **Host**, **Crewmates**, **Impostors**).
  * Controle de **Strength** (intensidade) e **Cooldown** (intervalo em ms).
  * **Auto Adapt:** Ajuste automático baseado no seu **PING** e taxa de **FPS**.
  * **Kill Switch on Lag:** Parada de segurança automática caso o ping ultrapasse o limite.
  * Logs detalhados de início, parada, alvos adicionados/removidos e desconexões.

---

### 🖥️ 11. Console, Perfis & Personalização (`ConsoleTab`, `ConsoleUI` & `ConfigTab`)
* **Console Integrado (`ConsoleUI`):** Registra em tempo real com horário e localização exata no mapa:
  * **Log Deaths** (mortes e tentativas bloqueadas por escudo)
  * **Log Shapeshifts** (transformações de Metamorfos)
  * **Log Vents** (quem entrou ou saiu de qual tubulação)
  * **Log Tasks** (tarefas concluídas por cada jogador)
  * **Log Game State** (início e fim de partida)
  * Botões para **Clear Log** e **Copy Log to Clipboard**.
* **Modos Visuais (`ModesTab`):**
  * **RGB Mode:** Efeito arco-íris dinâmico na interface do menu.
  * **Stealth Mode:** Oculta elementos visuais do mod na tela.
  * **Panic Mode (`PanicCleaner`):** Desativa e limpa instantaneamente todos os recursos ativos do mod com um clique.
* **Sistema de Perfis (`MalumProfile.txt`):**
  * **Save to Profile / Load from Profile:** Salva todas as suas opções ativadas e atalhos de teclado (`Keybinds`) personalizadas para carregar automaticamente ao abrir o jogo.
  * **Open Config / Reload Config:** Abre e recarrega o arquivo de configuração diretamente pelo menu.

---

## 🧹 Como Remover o Mod e Restaurar o Jogo Original

1. Feche o **Among Us**.
2. Abra a pasta de instalação do jogo.
3. Apague (ou mova para backup) os arquivos adicionados pelo mod (`BepInEx`, `dotnet`, `winhttp.dll`, `doorstop_config.ini`, etc.).
4. Verifique a integridade dos arquivos pela sua loja:
   * **Steam:** Botão direito no jogo → **Propriedades** → **Arquivos instalados** → **Verificar integridade dos arquivos**.
   * **Epic Games:** Três pontos (`...`) → **Gerenciar** → **Verificar**.

---

## 🛠️ Solução de Problemas

| Sintoma | O que fazer |
| :--- | :--- |
| **Aviso de versão incompatível no Menu Principal** | O mod foi compilado para a versão `2026.9.29`. Verifique se o seu jogo está nessa versão ou baixe uma release atualizada. |
| **O jogo abre normal, mas o menu não aparece ao apertar `Delete`** | Verifique se você jogou os arquivos na **raiz** da pasta (onde está o `Among Us.exe`) e não dentro de uma subpasta extra. |
| **O antivírus apagou o `winhttp.dll` ou a pasta `BepInEx`** | Arquivos de injeção `.dll` costumam gerar falsos positivos. Adicione a pasta do *Among Us* às exceções do Windows Defender e extraia novamente. |
| **Erro ao entrar na sala Online com amigos** | Para funções de **Host-Only** e **Force Role**, certifique-se de que você é o anfitrião (*Host*) da sala. |

---

## 📜 Créditos

* **Base Original (`MalumMenu`):** `scp222thj` & `Astral` (`astra1dev`)
* **Edição & Personalização Visual:** `Olofmaike`
