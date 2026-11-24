<div align="center">
  <img src="assets/wireless-battery-banner.svg" alt="Wireless Battery — baterias dos periféricos na barra do Windows" width="100%">

  <br>

  <a href="https://github.com/SRdorki/wireless-battery/raw/refs/heads/main/WirelessBatterySetup.exe"><img src="https://img.shields.io/badge/BAIXAR-Windows%2010%20%2F%2011-0878D1?style=for-the-badge&logo=windows&logoColor=white" alt="Baixar para Windows 10 e 11"></a>
  <img src="https://img.shields.io/badge/VERS%C3%83O-1.0.0-6FE0B8?style=for-the-badge" alt="Versão 1.0.0">
  <img src="https://img.shields.io/badge/ATUALIZA%C3%87%C3%83O-autom%C3%A1tica-6875E8?style=for-the-badge" alt="Atualizações automáticas">

  <p><strong>As baterias dos seus periféricos, direto na barra de tarefas.</strong></p>
</div>

## ✨ O que ele faz

- Mostra ícones e porcentagens em uma faixa compacta que acompanha a quantidade de dispositivos.
- Permite personalizar cores, fundo, ícones, nomes e informações exibidas.
- Lê o Attack Shark X11 pela dock/receptor e pelo cabo USB.
- Detecta periféricos Bluetooth quando o Windows disponibiliza a bateria.
- Exibe o raio enquanto o X11 carrega pelo cabo ou informa carregamento pelo receptor.

## ⬇️ Instalação

1. [Baixe o instalador](https://github.com/SRdorki/wireless-battery/raw/refs/heads/main/WirelessBatterySetup.exe).
2. Execute `WirelessBatterySetup.exe` e clique em **Instalar**.
3. Deixe marcada a opção **Iniciar automaticamente com o Windows** para manter a faixa após entrar no sistema.

O instalador é por usuário e coloca o aplicativo em `%LOCALAPPDATA%\Programs\Wireless Battery`.

## 🔄 Atualizações automáticas

O app consulta [`latest.json`](latest.json) ao iniciar e a cada seis horas. Quando há uma versão mais recente, baixa o pacote, confere o SHA-256 e reinicia com a atualização aplicada.

Os downloads ficam na branch `main`, na raiz do repositório. Para atualizar, publique o novo instalador, o pacote ZIP, o checksum e ajuste a versão e os links em `latest.json`.

## 📦 Arquivos

| Arquivo | Para que serve |
| --- | --- |
| [WirelessBatterySetup.exe](WirelessBatterySetup.exe) | Instalar ou remover o aplicativo |
| [Baterias-dos-perifericos.zip](Baterias-dos-perifericos.zip) | Pacote aplicado pelo atualizador |
| [Baterias-dos-perifericos.zip.sha256](Baterias-dos-perifericos.zip.sha256) | Conferir a integridade do pacote |
| [latest.json](latest.json) | Informar a versão e os endereços dos arquivos |

## ℹ️ Compatibilidade

O Windows só informa a bateria de periféricos que expõem esse dado. Alguns dispositivos Bluetooth não fornecem porcentagem. Docks de outras marcas podem exigir suporte específico.

## 🔒 Privacidade

As leituras dos periféricos são feitas localmente. A conexão à internet é usada para consultar o feed público e baixar atualizações; o app não envia dados de uso.
