# Diogo Conceição

Desenvolvedor de software baseado no Rio de Janeiro 🇧🇷, quase no fim da graduação em Ciência da Computação.

Gosto de construir ferramentas que eu e as pessoas ao meu redor realmente usamos — aplicações desktop, sistemas web e mobile que resolvem problemas concretos, com atenção genuína a arquitetura e experiência de uso. Nas horas vagas, estou provavelmente lendo um livro, assistindo a um filme, ou levantando peso.

### 🛠️ Stack

**Linguagens**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=for-the-badge&logo=rust&logoColor=white)

**Frontend & Desktop**

![React](https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black)
![Electron](https://img.shields.io/badge/Electron-47848F?style=for-the-badge&logo=electron&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=for-the-badge&logo=tauri&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white)
![SCSS](https://img.shields.io/badge/SCSS-CC6699?style=for-the-badge&logo=sass&logoColor=white)

**Backend & Ferramentas**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Zustand](https://img.shields.io/badge/Zustand-443E38?style=for-the-badge)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

### 🚀 Projetos em destaque

#### 🔹 LegacyReader — [biblioteca](https://github.com/DiogoConcei/biblioteca)

> Aplicação desktop completa para leitura de quadrinhos, mangás e livros digitais. Suporta `.cbr`, `.cbz`, `.pdf` vetorial e `.epub` com e-reader avançado (temas, tipografia, navegação por capítulos via CFI). Inclui servidor **LAN Sharing** com pareamento via QR Code e descoberta por mDNS, permitindo ler a coleção em qualquer dispositivo na rede local com sincronização de progresso em tempo real. Resolve o problema do `MAX_PATH` do Windows via virtualização de caminhos. Construída com **Electron**, **React**, **TypeScript**, **Sharp** e **Express**.

#### 🔹 Seeker — [PudimRobot](https://github.com/DiogoConcei/Seeker_PudimRobot) · [Pudim-Client](https://github.com/DiogoConcei/Seeker_Pudim-Client) *(em unificação)*

> Sistema de visão computacional embarcada para detecção e rastreamento humano em tempo real. O servidor de inferência (**Python + FastAPI**) recebe frames via **WebSocket**, aplica um filtro de movimento por diferença de pixels (FrameGate) para evitar processamento desnecessário, e passa os frames relevantes pelo **YOLOv8** para detecção de pessoas. Calcula distância por estimativa dinâmica de ombros, erro lateral para controle direcional e suaviza os dados com **EMA** para eliminar jitter. Opera em múltiplas estratégias de inferência (incluindo o modo `HYBRID_SENTINEL`, que entra em modo contínuo ao detectar movimento). O cliente roda em **ESP32** via **MicroPython**, capturando frames com câmera e controlando os motores do robô com base nas coordenadas recebidas. Descoberta automática do servidor via **mDNS** sem IP fixo.

#### 🔹 Personal Writer — [personal-writer](https://github.com/DiogoConcei/Personal-Writer)

> Editor de notas desktop local-first com dois modos de trabalho: editor rich-text com suporte a Markdown via **TipTap 3**, e um **infinite canvas** para organização espacial livre de notas, imagens e PDFs. Dicionário ortográfico PT-BR e sinônimos offline integrados via **Rust**. Histórico de versões com snapshots automáticos e marcos congeláveis. Construído com **Tauri 2**, **React 19** e **TypeScript**, com backend em Rust para operações de I/O e processamento de linguagem.

---

### 🎯 Próximos projetos

- 🎵 **Playlist Bridge** — Conversor de playlists entre Spotify e YouTube com integração das duas APIs, autenticação OAuth e geração de playlists por gênero e artistas mais ouvidos. (Python)
- 🎬 **Watch Together** — Plataforma web + mobile para assistir vídeos sincronizados com amigos, com suporte a arquivo local e streaming direto do computador. (em definição)
- 🎲 **Mesa Digital** — Aplicação de RPG de mesa com mapas interativos, disponível em web e mobile. (em definição)
