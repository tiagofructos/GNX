<h1 align="center">GNX</h1>

O GNX nasceu da ideia de simplificar a vida que quem tem um Nintendo Switch modificado. Como você mesmo pode notar pelo README, a cena do switch é extremamente fragmentada e composta por vários __Devs__ diferentes que possuem seus respectivos projetos, com isso, fica meio inviável para um iniciante saber oque baixar e como configurar tudo. Por isso o grandiosíssimo [Goma1337](https://github.com/Goma1337) criou um pacote AIO (All in One) com tudo que você precisa para usar no seu Switch.

<div align="center">
<img src="./Images/background.png" alight-itens="center">
</div>

[![Discord](https://img.shields.io/discord/570641761937129484?color=5662f6&label=GNX%20Server&logo=DISCORD&logoColor=5662f6&style=plastic)](https://discordapp.com/invite/8uhDqyx)
[![GitHub contributors](https://img.shields.io/github/contributors/vncsmnl/GNX)](https://github.com/vncsmnl/GNX/graphs/contributors)
[![GitHub All Releases](https://img.shields.io/github/downloads/vncsmnl/GNX/total)](https://github.com/vncsmnl/GNX/releases)
[![GitHub repo size](https://img.shields.io/github/repo-size/vncsmnl/GNX)](https://github.com/vncsmnl/GNX/find/main)
[![GitHub issues](https://img.shields.io/github/issues/vncsmnl/GNX)](https://github.com/vncsmnl/GNX/issues)
[![License](https://img.shields.io/badge/License-GPLv3-blue.svg)](https://www.gnu.org/licenses/gpl-3.0.en.html)

## 1) **🚦 BOOTLOADER:**

- [Hekate](https://github.com/CTCaer/hekate/releases): Payload utilizada pelo GNX. Serve para "organizar" o desbloqueio e possui diversas funcionalidades úteis como formatação de SD, criação de EmuNAND, toggle de AutoRCM, etc.

## 2) **🌌 CFW:**

- [Atmosphère](https://github.com/Atmosphere-NX/Atmosphere/releases): A custom firmware em si, que possibilita o uso de todos os recursos inclusos no pacote.

## 3) **🧩 HOMEBREWS:**

- [aio-switch-updater](https://github.com/HamletDuFromage/aio-switch-updater/releases): Software que atualiza diversos arquivos úteis para um switch desbloqueado. Por padrão, ele vem no pacote com vários recursos desativados, a fim de evitar que usuários mais leigos desconfigurem o GNX e acabem, entre outras coisas, banidos. Se voce não sabe o que está fazendo, use esse homebrew apenas para baixar cheats.

- [Homebrew App Store](https://www.switchbru.com/appstore/): Uma "loja de homebrews" mantida pela comunidade. Por ela você pode baixar outros softwares que não são inclusos no pacote.

- [DBI](https://github.com/rashevskyv/dbi/blob/main/README_ENG.md): Ferramenta multiúso. Faz de tudo um pouco. Mais detalhes aqui, cortesia do [Nintendo Unlock](https://www.youtube.com/watch?v=vH6kzvpZUJ4)

- [EdiZon](https://github.com/WerWolv/EdiZon/releases): Ferramenta para uso de cheats. Funciona também pelo Tesla Menu (L + Baixo no Dpad + R3)

- [Hekate Toolbox](https://github.com/WerWolv/Hekate-Toolbox/releases): Ferramenta para habilitar / desabilitar módulos de sistema e integrar algumas funcionalidades do Hekate dentro do Horizon (sistema operacional do Switch).

- [ldnmitm_config](https://github.com/spacemeowx2/ldn_mitm/releases): Homebrew para configuração do módulo ldn_mitm.

- [Linkalho](https://github.com/rdmrocha/linkalho): Homebrew para vincular e desvincular contas Nintendo. O vínculo é falso e serve apenas para enganar jogos que têm esse requerimento.

- [Tinfoil](https://tinfoil.io/Download#download) com `locations.config` do [Party Shop](https://partyshop.xyz), do [Turtle-in-the-Shop](http://titz.cf/), do [UnderPrivlidged Shop](http://rebrand.ly/UPStash), do [Pengu's Shop](http://pengu.us/), do [Stealth Shop](http://stealthshop.cf), do [Quota Shop](http://quotanx.in), do [ReDUMP Shop](https://redump.cf/) e do [Neko Shop](https://nekoshop.cf/), além da lista de shops do [Carcaschoi](https://github.com/carcaschoi/tinfoil-json).
  Instalador de jogos mais popular da cena do Switch, com a capacidade de conectar-se a servidores e baixar jogos diretamente pelo console, além de ter uma grande gama de outras funcionalidades.

- [Lockpick_RCM](https://github.com/shchmue/Lockpick_RCM/releases): Payload para dumpar as keys do seu console (diversos softwares precisam das keys para funcionar, com oo NxNandManager).

- [Homebrew Menu](https://github.com/switchbrew/nx-hbmenu/releases): O menu que substitui o álbum e / ou jogos (se você os abrir segurando R) e possibilita o uso de homebrews.

- [NX-Activity-Log](https://github.com/tallbl0nde/NX-Activity-Log): Homebrew que monitora de maneira detalhada o tempo de uso de cada jogo.

- [NXThemesInstaller](https://github.com/exelix11/SwitchThemeInjector/releases): Instalador de temas. Sempre utilize essa ferramenta para remover seus temas ANTES de atualizar a firmware do console.

- [prodinfo_gen](https://github.com/CaramelDunes/prodinfo_gen/releases/): Payload capaz de gerar uma prodinfo falsa, útil para salvar consoles com a prodinfo brickada. A prodinfo gerada pelo console NÃO serve para jogar online, agindo apenas como um "incognito" mais sofisticado. O usuário comum não precisa mexer com isso.

- [Reset Parental Controls](https://github.com/ITotalJustice/Reset-Parental-Controls-NX/releases): Software capaz de remover os controles parentais mesmo sem a senha.

- [TegraExplorer](https://github.com/suchmememanyskill/TegraExplorer/releases): Payload com uma série de funcionalidades. Está no pacote primariamente para possibilitar o uso do script...
  -- SyncFix.te, localizado na pasta TegraExplorer. Ele serve para sincronizar os controles e conexões da SysNAND para a EmuNAND, evitando assim a necessidade de ressincronizar os controles cada vez que alternar entre as NANDs.

## 4) **💡 MÓDULOS DE SISTEMA PARA O ATMOSPHÈRE**

Podem ser habilitados ou desabilitados pelo homebrew Hekate Toolbox ou pelo Tesla Menu (L + D-pad para Baixo + R3):

- [Emuiibo](https://github.com/XorTroll/emuiibo/releases): Módulo capaz de emular amiibos. Os amiibos já são inclusos no pacote, mas podem ser gerados no pelo Emutool, também incluso. Depois de habilitado o módulo, escolha o amiibo pelo Tesla Menu (L + D-pad para Baixo + R3).

- [sys-ftpd-light](https://github.com/cathery/sys-ftpd-light/releases): Transforma o Switch num servidor de FTP, possibilitando a transferência de arquivos por rede local com o auxílio de uma ferramenta como o Filezilla.

- [sys-clk](https://github.com/retronx-team/sys-clk/releases): Serve para realizar overclock no console e pode ser configurado pelo Tesla Menu (L + D-pad para Baixo + R3) graças ao...
  -- [sys-clk-Overlay](https://github.com/Sun-Research-University/sys-clk-Overlay/releases)

- [ldn_mitm](https://github.com/spacemeowx2/ldn_mitm/releases): Transforma a funcionalidade de local multiplayer em Lan, possibilitando assim o uso do Lan Play em jogos que não têm a funcionalidade de Lan nativamente.

- [Mission Control](https://github.com/ndeadly/MissionControl/releases): Possibilita o uso de controles bluetooth de outras plataformas no Switch. Para usar, habilite o módulo, reinicie o console e sincronize o controle pelo menu do Switch, como faria com um controle da Nintendo. Para mais detalhes de como sincronizar cada controle, visite o Github.

- [sys-con](https://github.com/cathery/sys-con/releases): Possibilita o uso de controles de outras plataformas no Switch contanto que estejam conectados por cabo. Apesar dessa desvantagem em relação ao Mission Control, possui compatibilidade com mais controles.

- [sys-screenuploader](https://github.com/bakatrouble/sys-screenuploader/releases): Faz upload de screenshots e capturas de vídeo para o Discord ou Telegram. Por padrão, vem configurado para subir as capturas para o #sys-screenuploader do servidor de [Discord do GNX](http://tiny.cc/DiscordGNX). Isso pode ser modificado [AQUI](https://screenuploader.bakatrouble.me/)

- [SysDVR](https://github.com/exelix11/SysDVR/releases): Realiza streaming de áudio e vídeo do console para um PC, funcionando tanto por rede local como por cabo USB. Para maiores detalhes de como usar, visite o wiki do projeto [AQUI](https://github.com/exelix11/SysDVR/wiki)

- [Sys-Botbase](https://github.com/olliz0r/sys-botbase/releases): Módulo que possibilita a programação de bots e edição de ram em tempo real por rede. Trabalha em conjunto com o PKHeX, SysBot.Net, NHSE, entre outros projetos.

- [Tesla Menu](https://github.com/WerWolv/Tesla-Menu/releases): Menu que pode ser aberto a qualquer momento com a combinação de botões L + D-pad para Baixo + R3. Serve para configurar módulos, exibir informações e várias outras coisas.

- [nx-ovlloader](https://github.com/WerWolv/nx-ovlloader/releases): Componente necessário para o funcionamento do Tesla Menu.

- [ovlSysmodules](https://github.com/WerWolv/ovl-sysmodules/releases): Componente do Tesla Menu que exibe os toggles de módulo de sistema.

- [Status Monitor Overlay](https://github.com/masagrator/Status-Monitor-Overlay/releases): Componente do Tesla Menu que exibe informações em tempo real como temperatura, porcentagem de uso dos recursos do sistema, etc.

- [SaltyNX](https://github.com/masagrator/SaltyNX/releases): Framework para possibilitar alguns truques de performance como o...

  - [ReverseNX-RT](https://github.com/masagrator/ReverseNX-RT/releases), que "engana" o console, forçando-o a pensar que está dockado no modo portátil e vice-versa.

- [sys-tune](https://github.com/HookedBehemoth/sys-tune/releases): Player de música em plano de fundo, acessível pelo Tesla Menu.

## 5) **🖥️ SOFTWARES PARA USO NO PC:**

- [TegraRcmGUI Portable e Installer](https://github.com/eliboa/TegraRcmGUI/releases): Injetor de payload.

- [GUIformat](http://www.ridgecrop.demon.co.uk/index.htm?guiformat.htm): Ferramenta para formatar o cartão SD em Fat32 (recomendado). Não funciona se alguma janela do Windows Explorer estiver aberta.

- [PKHeX + Plugins](https://github.com/architdate/PKHeX-Plugins/releases/): Melhor editor de saves para os jogos mainline de Pokémon. Rode o almsetup_stable.exe para baixar a última versão do PKHeX e do plugin Auto Legality Mod.

## 🤝 Colaboradores

Agradecemos às seguintes pessoas que contribuíram para este projeto:

<table>
  <tr>
    <td align="center">
        <a href="https://github.com/Goma1337">
            <img src="https://avatars.githubusercontent.com/u/57841969?v=4" width="100px;" alt="Foto do Goma no GitHub"/><br>
            <sub>
            <b>Goma1337</b>
            </sub>
        </a>
    </td>
    <td align="center">
        <a href="https://github.com/vncsmnl">
            <img src="https://avatars.githubusercontent.com/u/59481808?v=4" width="100px;" alt="Foto do Vinícius Manoel no GitHub"/><br>
            <sub>
                <b>Vinícius Manoel</b>
            </sub>
        </a>
    </td>
  </tr>
</table>

## 📝 Licença

![License](https://img.shields.io/badge/License-GPLv3-blue.svg)

The Nintendo Switch names and logos are [Nintendo](https://github.com/Nintendo). This repository is in no way affiliated with [Nintendo](https://github.com/Nintendo) or any of its partners.
