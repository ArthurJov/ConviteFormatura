# Convite de Formatura Digital — Ludmila Paixão

Este é um site mobile-first de convite de formatura premium para Ludmila Paixão (Estética e Cosmética 2026).

## Características

- **Mobile-First & Snap Scroll**: Criado especificamente para proporcionar uma experiência fluida no celular.
- **Tipografia Cinética**: Animações de entrada letra a letra no nome principal (agora com quebras de linha automáticas e responsivas, impedindo corte no meio da palavra).
- **Parallax de Profundidade**: Efeitos interativos que respondem ao movimento do mouse e à inclinação do celular (giroscópio), além de parallax progressivo e suave durante o scroll.
- **Partículas em Canvas**: Efeitos elegantes de partículas douradas flutuantes na tela inicial e "confetti" na tela final, renderizados via HTML5 Canvas.
- **Trilha Sonora**: Botão interativo para reproduzir áudio ambiente.

## Estrutura de Arquivos

- `index.html`: Arquivo principal contendo toda a estrutura HTML, estilização CSS (Tailwind/Vanilla) e scripts integrados. Sem dependências externas além do Google Fonts.
- `img/`: Pasta contendo as imagens utilizadas no convite (`hero.jpg`, `closing.jpg`, etc).
- `audio/`: Pasta com o arquivo de áudio de fundo (`background.mp3`).

## Configurações Editáveis (Variáveis)

Dentro do arquivo `index.html`, logo no início da tag `<script>`, existem variáveis de fácil edição para configurar o evento sem precisar mexer em códigos complexos:

```javascript
const EVENT_DATE      = new Date('2026-08-02T15:00:00-03:00');
const RSVP_DEADLINE   = '[DATA A DEFINIR]';
const WHATSAPP_NUMBER = '5571982080832';
const AUDIO_SRC       = 'audio/background.mp3';
```

## Como Visualizar

Para experimentar o convite em sua capacidade máxima:
1. Abra o arquivo `index.html` no Google Chrome ou Safari.
2. Para testar a responsividade, utilize o DevTools (F12) simulando a visualização em dispositivos móveis (ex: iPhone 14, Galaxy S22).
3. Caso queira testar a animação giroscópica de parallax, hospede o site (via GitHub Pages, Vercel ou Live Server configurado) e acesse através do seu smartphone.
