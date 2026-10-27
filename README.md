<h1 align="center">🎮 Memoria7 — Ferramentas para Streaming</h1>
<p align="center"><strong>Projeto pessoal de desenvolvimento Front-End aplicado a transmissões ao vivo</strong></p>
<p align="center">
<img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white"/>
<img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white"/>
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"/>
<img src="https://img.shields.io/badge/OBS%20Studio-302E31?style=for-the-badge&logo=obsstudio&logoColor=white"/>
</p>

## 📺 Sobre o projeto

O **Memoria7 (M7)** é meu projeto pessoal de conteúdo sobre games, nostalgia e experiências compartilhadas em família. Neste repositório, reúno interfaces e recursos técnicos desenvolvidos para as transmissões, colocando em prática conceitos de **HTML, CSS, JavaScript, animações e integração visual com o OBS Studio**.

Este portfólio documenta tanto a criação de componentes visuais quanto os desafios de configurar e testar elementos em cenas reais de streaming.

## 🚀 Projetos e recursos

### ⚔️ Dark Souls II — overlay interativo

- [Overlay original em HTML](overlays/dark-souls-2/memoria7_overlay.html)
- [Overlay V2 com painel e efeitos](overlays/dark-souls-2/Memoria7_DarkSouls2_Overlay_V2.html)
- [Guia de configuração e testes no OBS](docs/GUIA_MEMORIA7_OVERLAY_V2.txt)

**Recursos explorados:** composição de uma tela 1920 × 1080, moldura para webcam, painéis visuais, animações em CSS, ajustes de posicionamento e simulações de alertas em JavaScript.

**Atalhos do overlay V2** (na janela **Interagir** da fonte Navegador):

| Tecla | Função |
| --- | --- |
| T | Mostrar/ocultar painel de configuração |
| F1 | Simular novo seguidor |
| F2 | Simular inscrição |
| F3 | Simular doação |
| F4 | Simular batalha contra chefe |
| F5 | Simular derrota |

> ⚠️ Os alertas de seguidor, inscrição e doação funcionam em **modo de demonstração**. Este código não comprova integração automática com eventos reais da Twitch, do YouTube ou do StreamElements.

> ℹ️ Para manter o repositório leve, o arquivo V2 publicado usa a marca textual **M7** no lugar da imagem do logotipo incorporada ao arquivo de trabalho original. O restante do código foi mantido.

### 🏎️ Need for Speed: Most Wanted
Projeto de lives e vídeos do canal. Já temos uma **tela de pausa** na galeria visual. **O código do overlay interativo específico ainda está pendente de recuperação.**

### 🗡️ Hollow Knight
Conteúdo de transmissões e vídeos curtos, agora com **arte visual disponível na galeria**. **Arquivos técnicos de overlay pendentes de recuperação.**

### 👨‍👦 Lives em família — Cuphead, Mario e outros jogos
Experiências de transmissões com meu filho, envolvendo identidade visual e organização de cenas. **Arquivos de overlays e alertas específicos ainda não publicados neste repositório.**

## 🖼️ Galeria visual — materiais já publicados

Esta seção reúne algumas artes, miniaturas e telas utilizadas ou preparadas para o canal. **As imagens demonstram o trabalho de identidade visual e produção; não substituem os arquivos HTML dos overlays interativos.**

### 💜 Identidade do Memoria7

![Logo Gamer M7 com Texto MEMORIA7](imagens/Logo%20Gamer%20M7%20com%20Texto%20MEMORIA7.png)

### 🎥 Cenas de transmissão

**Tela de início de live**

![Tela Live já vai começar](imagens/Live%20ja%20vai%20come%C3%A7ar.png)

**Tela de pausa para Need for Speed: Most Wanted**

![Tela de pausa da live Most Wanted](imagens/pausa%20live%20most.png)

**Arte de overlay**

![Arte de overlay do Memoria7](imagens/overlay.png)

### 🎮 Miniaturas e artes de conteúdo

| Dark Souls II | Hollow Knight |
| --- | --- |
| ![Miniatura Dark Souls II](imagens/thumb%20dark%20souls%202.png) | ![Arte Hollow Knight](imagens/hollow%20knigth.png) |

| Kingdom Hearts | Outra miniatura do canal |
| --- | --- |
| ![Miniatura Kingdom Hearts](imagens/A%20dor%20das%20%C3%BAltimas%20vezes%20Kingdom%20Hearts%20e%20as%20despedidas%20que%20nos%20mudam%20%F0%9F%95%B0%EF%B8%8F-Miniatura.jpg) | ![Miniatura thumb mody](imagens/thumb%20mody.png) |

### 🎞️ Vídeo de encerramento

[▶️ Conferir vídeo de encerramento do Memoria7](imagens/memoria7_short_encerramento_sem_marca.mp4)

Outros arquivos visuais podem ser consultados na [pasta de imagens](imagens/). As artes adicionais permanecem preservadas com seus nomes originais.

---

## 🛠️ Como usar o overlay com OBS Studio

1. Configure uma cena do OBS em **1920 × 1080**.
2. Adicione o jogo à cena e ajuste-o à tela.
3. Adicione uma **Fonte Navegador** e marque a opção **Arquivo local**.
4. Selecione o arquivo HTML do overlay e defina largura **1920** e altura **1080**.
5. Posicione a webcam atrás da moldura do overlay, conforme as fontes da cena.
6. Para testar as interações, use **Interagir** na fonte Navegador e os atalhos da tabela acima.

O guia detalhado está em [docs/GUIA_MEMORIA7_OVERLAY_V2.txt](docs/GUIA_MEMORIA7_OVERLAY_V2.txt).

## 🧠 Conhecimentos aplicados

`HTML semântico` · `CSS` · `Animações` · `JavaScript` · `Interfaces personalizadas` · `Testes de interação` · `OBS Studio` · `Organização de projetos`

Na produção do canal também utilizo **Filmora** para edição de vídeos. Essa atividade é complementar ao desenvolvimento dos overlays.

## 🔐 Segurança e uso responsável

Este repositório não deve armazenar senhas, tokens de serviços de streaming, dados pessoais de seguidores ou credenciais de integração. Imagens, músicas e outros elementos de jogos de terceiros exigem atenção às licenças e direitos autorais.

## 🧭 Próximas melhorias

- Documentar e incorporar overlays de outras transmissões conforme os arquivos forem recuperados;
- Separar melhor estilos e scripts em arquivos reutilizáveis;
- Complementar a galeria com capturas reais das cenas no OBS;
- Testar integração real com eventos de alertas, sem expor credenciais;
- Explorar um projeto de análise de métricas do canal usando SQL, Python ou Power BI.

---

<p align="center"><em>O tempo muda a gente, mas memórias boas nunca dão reset.</em> 💜</p>
