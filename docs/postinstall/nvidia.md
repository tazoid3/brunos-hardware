---
sidebar_position: 3
---

# Painel de Controlo da NVIDIA

Este guia irá abordar as definições que precisas de ajustar para obter latência mínima, FPS elevados e bons frametimes.

:::info

Só aplicável a placas gráficas NVIDIA. Certifica-te que tens instalado os drivers antes de começar.

:::

## Abrir o Painel de Controlo da NVIDIA

- Carrega com o botão direito na área de trabalho e carrega em `NVIDIA Control Panel` no menu.

## Adjust Image Settings with Preview

- Carrega em `Use my preference emphasizing:`
- Arrasta até `Performance`
- Carrega em `Apply`
- Carrega em `Use the advanced 3D image settings`

Ao aplicar a predefinição `Performance`, garante-nos uma boa fundação que nos poupará tempo na próxima etapa.

## Manage 3D Settings

Se não conseguires ver algumas das definições listadas abaixo, simplesmente ignora e passa para a próxima.

Certifica-te de que as tuas definições correspondem ao seguinte:

**Global Settings:**

- Image Sharpening: Off
- Ambient Occlusion: Off
- Anisotropic filtering: Application-controlled
- Antialiasing - FXAA: Off
- Antialiasing - Gamma correction: Off
- Antialiasing - Mode: Application-controlled
- Antialiasing - Setting: None
- Antialiasing - Transparency: Off
- CUDA - GPUs: All
- DSR - Factors: Off
- DSR - Smoothness: Off
- Low Latency Mode: On
- Monitor Technology: Fixed Refresh
- Multi-Frame Sampled AA (MFAA): Off
- OpenGL rendering GPU: [your GPU]
- Power management mode: Prefer maximum performance
- Preferred refresh rate (monitor name): Highest available
- Shader Cache: On
- Texture filtering - Anisotropic sample optimization: On
- Texture filtering - Negative LOD bias: Allow
- Texture filtering - Quality: High performance
- Texture filtering - Trilinear optimization: On
- Threaded optimization: Auto
- Triple buffering: Off
- Vertical sync: Off
- Virtual Reality pre-rendered frames: 1

Quando terminares, carrega em `Apply`.