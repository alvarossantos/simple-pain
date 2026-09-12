# SimplePaint

Aplicativo Android de pintura que permite desenhar livremente na tela com diferentes cores.

## Funcionalidades

- Desenho livre na tela com suavização de traços (bezier curves)
- 4 cores disponíveis: **Verde**, **Azul**, **Vermelho** e **Magenta**
- Botão Limpar para apagar o desenho

## Estrutura do Projeto

```
app/src/main/java/br/edu/uemg/simplepaint/
├── MainActivity.java   - Activity principal, gerencia botões de cor e limpar
├── ViewCanvas.java     - View customizada que recebe toques e desenha no canvas
├── Linha.java          - Modelo que associa um Path a um Paint para desenhar
└── Estilo.java         - Fábrica de estilos (cores e espessura dos traços)
```

## Tecnologias

- Java
- Android SDK (API 35)
- Gradle 9.7.1 / AGP 9.4.0

## Como Rodar

1. Abra o projeto no Android Studio
2. Sincronize o Gradle (File → Sync Project with Gradle Files)
3. Execute em um emulador ou dispositivo físico com API 23+
