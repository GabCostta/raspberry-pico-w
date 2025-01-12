# EmbarcaTech - Raspberry Pico W - GitDogLab

Este repositório faz parte do projeto **Residência em Sistemas Embarcados (EmbarcaTech), realizado no IFCE.** Ele contém instruções detalhadas para configurar o ambiente e programar o **Raspberry Pi Pico** na placa **BitDogLab**.

---

## Sumário
1. [Introdução](#introdução)
2. [Pré-requisitos](#pré-requisitos)
3. [Passos de Configuração](#passos-de-configuração)
   - [Instalação do VS Code](#1-instalação-do-vs-code)
   - [Instalação do Compilador ARM GCC](#2-instalação-do-compilador-arm-gcc)
   - [Instalação do Raspberry Pi Pico SDK](#3-instalação-do-raspberry-pi-pico-sdk)
   - [Configuração de Variáveis de Ambiente](#4-configuração-de-variáveis-de-ambiente)
   - [Plugins do VS Code](#5-plugins-do-vs-code)
4. [Recursos Úteis](#recursos-úteis)
5. [Contribuindo](#contribuindo)
6. [Licença](#licença)

---

## Introdução

O objetivo deste repositório é auxiliar na configuração de um ambiente de desenvolvimento para programação do **Raspberry Pi Pico** com suporte ao **ARM GCC Toolchain** e ao **Pico SDK**. O guia abrange desde a instalação de ferramentas até a configuração de variáveis de ambiente e extensões do VS Code.

---

## Pré-requisitos

- Computador com **Windows**.
- Conhecimento básico de sistemas embarcados.
- Acesso à internet para download das ferramentas.

---

## Passos de Configuração

### 1. Instalação do VS Code
- Faça o download do [Visual Studio Code](https://code.visualstudio.com/) e instale a versão mais recente.
- Configure o VS Code para trabalhar com C/C++.

---

### 2. Instalação do Compilador ARM GCC
1. Baixe o **ARM GNU Toolchain** no formato `.exe` através do link abaixo:
   - [ARM GNU Toolchain 13.3.rel1](https://developer.arm.com/-/media/Files/downloads/gnu/13.3.rel1/binrel/arm-gnu-toolchain-13.3.rel1-mingw-w64-i686-arm-none-eabi.exe).
2. Durante a instalação:
   - Anote o diretório de instalação (ex.: `C:\Program Files (x86)\Arm GNU Toolchain arm-none-eabi\13.3 rel1`).
   - Marque a opção **Add Path to environment variable** na última etapa do instalador.

---

### 3. Instalação do Raspberry Pi Pico SDK
1. Baixe o instalador do Raspberry Pi Pico SDK:
   - [Pico Setup](https://github.com/raspberrypi/pico-setup-windows/releases).
2. Siga o instalador até o final, certificando-se de marcar a opção **Add path to environment variable**.

---

### 4. Configuração de Variáveis de Ambiente
1. Abra as configurações de variáveis de ambiente do Windows:
   - Clique com o botão direito em **Meu Computador** > **Propriedades** > **Configurações avançadas do sistema** > **Variáveis de Ambiente**.
2. Adicione ao `PATH`:
3. Adicione as seguintes variáveis do sistema:
- `PICO_SDK_PATH` = `C:\Program Files\Raspberry Pi\Pico SDK v1.5.1`
- `PICO_TOOLCHAIN_PATH` = `C:\Program Files\Raspberry Pi\Pico SDK v1.5.1\pico-sdk\toolchain`

---

### 5. Plugins do VS Code
Instale as seguintes extensões no VS Code:
- **C/C++**: Suporte ao desenvolvimento em C/C++.
- cmake
- Cmaketolls
- Raspberry pi pico
- instalar em realeses a versao windowns setup raspberry pi pico v1.5.1 


---

---

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo [LICENSE](LICENSE) para mais informações.

