# Block Fall

Jogo de blocos inspirado nos clássicos, desenvolvido em **Lua** com o framework **LÖVE 11.x**.

## Recursos

- Menu principal com Iniciar Partida, Configurações e Sair do Jogo
- Tabuleiro com peças coloridas, rotação e queda instantânea
- Pontuação, linhas eliminadas, níveis e tela de fim de jogo
- Configurações de dificuldade e grade
- Música chiptune original e efeitos sonoros WAV
- Controles por teclado

## Requisitos

- Windows (para o inicializador `.bat`)
- [LÖVE 11.x para Windows](https://love2d.org/)

## Como executar

1. Instale o LÖVE.
2. Baixe ou clone este repositório.
3. Mantenha `main.lua`, `conf.lua` e a pasta `assets/` juntos.
4. Abra a pasta do projeto com o LÖVE. Se tiver o LÖVE disponível no PATH, também pode executar `love .` no terminal.
5. No Windows, o arquivo `iniciar.bat` tenta iniciar o projeto usando `love.exe` localizado na própria pasta. Se seu `love.exe` estiver instalado em outro local, ajuste o inicializador ou abra a pasta do projeto diretamente com o LÖVE.

## Controles

| Tecla | Ação |
|---|---|
| ← / → | Mover a peça |
| ↑ ou X | Girar a peça |
| ↓ | Acelerar a queda |
| Espaço | Queda instantânea |
| P | Pausar / continuar |
| Esc | Voltar ao menu; no menu, sair |

## Áudio

Os arquivos de áudio devem permanecer na pasta `assets/` com estes nomes:

- `music_loop.wav` — música de fundo
- `move.wav` — movimento
- `rotate.wav` — rotação
- `drop.wav` — queda instantânea
- `clear.wav` — linhas eliminadas
- `gameover.wav` — fim de jogo

## Estrutura

```text
BlockFall/
├── main.lua
├── conf.lua
├── iniciar.bat
├── README.md
├── .gitignore
└── assets/
    ├── music_loop.wav
    ├── move.wav
    ├── rotate.wav
    ├── drop.wav
    ├── clear.wav
    └── gameover.wav
```

## Estado do projeto

Versão inicial em desenvolvimento. Recursos e compatibilidade ainda podem mudar.
