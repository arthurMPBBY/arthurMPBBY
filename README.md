<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=220&section=header&text=arthurMPBBY&fontSize=48&fontAlignY=38&desc=Software%20Developer%20%7C%20Open%20Source%20Contributor&descFontSize=20&descAlignY=62" width="100%"/>
</div>

<div align="center">
  
  [![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com)
  [![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:arthurkadri968@gmail.com)
  [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/arthurMPBBY)

</div>

---

### 👨‍💻 Sobre mim / About Me

Olá! Sou desenvolvedor de software focado em performance, sistemas desktop e tecnologias multimídia/gráficas no Linux. Gosto de resolver desafios de baixo nível, renderização gráfica, pipelines de shaders e otimização de reprodução de vídeo.

- 🔭 **Atualmente:** Contribuindo ativamente com projetos open source e ferramentas de multimídia no Linux.
- ⚡ **Áreas de interesse:** Vulkan, Shaders (GLSL), C++, Kotlin / Compose Multiplatform, IoT, otimização de vídeo e Linux desktop.
- 💬 **Fale comigo sobre:** Linux, renderização gráfica, pipelines de shaders, mpv e desenvolvimento desktop.

---

### 🛠️ Tecnologias & Ferramentas / Tech Stack

<div align="center">

#### Linguagens
![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![GLSL](https://img.shields.io/badge/GLSL%20%2F%20Shaders-5586A4?style=for-the-badge&logo=opengl&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

#### Gráficos & Plataformas
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Vulkan](https://img.shields.io/badge/Vulkan-AC162C?style=for-the-badge&logo=vulkan&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)

</div>

---

### 🌟 Destaques & Projetos Open Source / Featured Projects

<table>
  <tr>
    <td width="100%">
      <h3><a href="https://github.com/arthurMPBBY/tuya-smart-lamps">💡 Tuya Smart Lamps Ecosystem</a></h3>
      <p>Ecossistema IoT local de altíssima performance para lâmpadas inteligentes Tuya v3.5, com latência sub-10ms e resiliência total:</p>
      <ul>
        <li><b>Controle Local TCP Sub-10ms:</b> Comunicação direta via soquetes persistentes com keepalive periódico de 12s e mutex desacoplado de I/O de rede.</li>
        <li><b>Servidor Web REST & SSE:</b> Transmissão em tempo real de mudanças de estado via Server-Sent Events para múltiplos clientes.</li>
        <li><b>App & Widget Nativo para Android:</b> Widget interativo de tela inicial com resposta tátil instantânea, 5 temas modernos (Frosted Glass, OLED, Cyberpunk, Emerald) e sequenciador anti-corrida.</li>
        <li><b>Fallback Híbrido Tuya OpenAPI:</b> Autonomia automática com roteamento direto para a nuvem Tuya via HMAC-SHA256 quando o servidor local está desligado ou o smartphone está fora da rede local.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="100%">
      <h3><a href="https://github.com/arthurMPBBY/gaming-fps-hud">🎮 Gaming FPS HUD & Vulkan Layer Observer</a></h3>
      <p>Overlay de performance ultraleve e camada de observação Vulkan para KDE Wayland e Linux:</p>
      <ul>
        <li><b>Camada Vulkan Explícita (<code>VK_LAYER_GamingFpsHud_present_observer</code>):</b> Intercepta <code>vkQueuePresentKHR</code> em nível de driver com medições precisas de frametime, framerate e jitter.</li>
        <li><b>Comunicação IPC via Shared Memory:</b> Sincronização em tempo real com zero overhead através de memória compartilhada POSIX (<code>shm_open</code>).</li>
        <li><b>Interface Fluida em Qt Quick / QML:</b> Overlay renderizado a alta taxa de quadros com gráfico de frametime em tempo real e visual inspirado no MangoHud.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="100%">
      <h3><a href="https://github.com/NuvioMedia/NuvioDesktop/pull/953">🚀 Nuvio Desktop — Linux Video Enhancements & PiP</a></h3>
      <p>Desenvolvimento e integração de recursos avançados de reprodução de vídeo para desktop Linux:</p>
      <ul>
        <li><b>Picture-in-Picture nativo</b> com gerenciamento X11 e tratamento seguro de ciclo de vida contra erros <code>BadWindow</code>.</li>
        <li><b>Backend Vulkan de alta performance</b> (<code>gpu-next</code> / <code>x11vk</code>) com aceleração de hardware VA-API para redução de latência e zero tearing.</li>
        <li><b>Motor de Upscaling em tempo real:</b> Integração dos shaders AMD FidelityFX Super Resolution 1.0 (EASU + RCAS), Contrast Adaptive Sharpening (CAS) e Anime4K A+A Fast.</li>
        <li><b>Integração com LSFG-VK</b> para geração de quadros por camada Vulkan.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 📊 Estatísticas / GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=arthurMPBBY&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Arthur's GitHub Stats" height="165"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=arthurMPBBY&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117" alt="Top Languages" height="165"/>
</div>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=arthurMPBBY&theme=tokyonight&hide_border=true&background=0D1117" alt="GitHub Streak" width="60%"/>
</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=0,2,2,5,30&height=100&section=footer" width="100%"/>
</div>
