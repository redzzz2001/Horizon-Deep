#   HORIZON DEEP — WebGPU Procedural Flight & Ocean Simulator


Um simulador de voo, exploração marítima e submarina fotorrealista construído **100% do zero em WebGPU e WGSL puro**, sem nenhuma engine externa e empacotado em **um único arquivo `.html` de ~461 KB** — basta baixar e abrir direto no navegador!

> *De oceanos com reflexos Ray-Traced a picos nevados, savanas douradas, florestas 3D e exploração submarina sem instalar nada.*

---

## 📸 Galeria (Capturas In-Game / Modo Foto)



| Voo a Noite |
| :---: |
|<img width="1919" height="1079" alt="Captura de tela 2026-11-23 215846" src="https://github.com/user-attachments/assets/ceebb430-d480-40ad-a70f-d89455fea920" />|


| Voo sobre o mar |
| :---: |
|<img width="1919" height="1079" alt="8" src="https://github.com/user-attachments/assets/5742bf37-704f-4ffd-a36c-fe5f5931c343" />|

---

## ✨ Principais Recursos

### 🎨 Engenharia Gráfica & Renderização (WGSL)
- **Arquivo Único & Zero Dependências (~461 KB):** Todo o motor gráfico, geometria, texturas PBR, terreno, aeronaves e efeitos atmosféricos são gerados matematicamente em tempo real via *Compute* e *Fragment Shaders* dentro de um único `.html`.
- **Ray Tracing em Tempo Real:** Sombras suaves (*Soft Shadows*), reflexos dinâmicos na água e na fuselagem metálica, além de *Ambient Occlusion (AO)* e *Global Illumination (GI) Bounce*.
- **Oceano Fotorrealista:** Múltiplas oitavas de *Perlin Noise*, transição de profundidade (azul abissal para verde-água raso), cáusticas subaquáticas e espuma na arrebentação das ondas.
- **Atmosfera & Clima Dinâmico:** Nuvens volumétricas (*Ray Marching*), ciclo completo de dia/noite com céu estrelado, *God Rays*, *Height Fog*, tempestades com raios iluminando as nuvens e gotas de chuva na lente.
- **Pós-Processamento Cinematográfico:** *Tone Mapping ACES Filmic*, *HDR Bloom*, *Nitidez CAS (Contrast Adaptive Sharpening)* e vinheta dinâmica.

### 🌍 Mundo Vivo & Exploração Anfíbia
- **Exploração Ar, Mar e Submarino:** Pilote um **P-51D** detalhado (com hélice com *motion blur* procedural), pouse na água ou mergulhe para explorar o fundo do oceano.
- **Biomas Procedurais:** Praias tropicais, cadeias montanhosas com neve procedural baseada em inclinação (*slope*), savanas douradas, florestas e áreas costeiras.
- **Ecossistema Dinâmico:** Grama 3D reativa ao vento e ao *downwash*, florestas 3D, animais terrestres, gaivotas e vida marinha (algas e peixes).

### 📷 Modo Foto Integrado
- Controle completo de **FOV (campo de visão)**, **Exposição**, **Hora do Dia**, **Clima** e **Poses pré-definidas da aeronave** para enquadramentos cinematográficos.


## 🚀 Como Jogar (Zero Instalação)

Não precisa instalar nada, nem rodar servidor local:

1. Baixe o arquivo **`.html`** deste repositório (ou clique em **Code → Download ZIP**).
2. Dê um **duplo clique no arquivo `.html`** para abrir direto no navegador (**Google Chrome**, **Microsoft Edge** ou **Opera** com suporte a **WebGPU** e aceleração de hardware ativados).
3. Escolha seu preset gráfico e decole!

<div align="center">

[![Jogar Agora](https://img.shields.io/badge/%E2%96%B6_JOGAR_HORIZON_DEEP-0077B6?style=for-the-badge)](https://horizondeep.vercel.app/)

*Roda direto no navegador (Chrome / Edge com WebGPU) — sem precisar baixar nada!*

</div>


## 🎮 Controles Básicos

| Tecla / Ação | Função |
| :--- | :--- |
| **`W` / `S`** | Arfagem (Mergulhar / Subir) |
| **`A` / `D`** | Rolagem (Inclinar asas) |
| **`Q` / `E`** | Leme (Guinada) |
| **`Shift` / `Ctrl`** | Aumentar / Reduzir Potência do Motor |
| **`P` ou Menu** | Abrir **Modo Foto** e ajustar clima, hora e poses |
| **`H`** | Ocultar / Mostrar HUD |

## IA
| Esse projeto foi gerado com IA usando o modelo Neon Do google pelo antigravity em varios prompts.

## 🛠️ Tecnologias Utilizadas

- **WebGPU API** (Render Pipelines, Compute Shaders, Storage Buffers, Depth/Color Attachments)
- **WGSL (WebGPU Shading Language)** para toda a matemática de ruído (*FBM*, *Ridged Multifractal*, *Perlin*), iluminação PBR e Ray Marching
- **HTML5 & Vanilla JavaScript (ES6+)** 100% auto-contido em arquivo único

---

## 📄 Licença

Este projeto foi desenvolvido como experimento criativo de computação gráfica procedural em WebGPU. Sinta-se à vontade para baixar, jogar, estudar os shaders e modificar!
