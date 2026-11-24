# Duelo de Canhões

## Nome do jogo

**Duelo de Canhões**

## Descrição geral

Duelo de Canhões é um jogo 2D de artilharia no qual o jogador comanda uma fortaleza equipada com um canhão e enfrenta uma fortaleza controlada pelo computador.

O objetivo é destruir a fortaleza adversária antes que a sua própria seja destruída. Para vencer, o jogador precisa ajustar o ângulo do canhão e controlar a potência dos disparos. A máquina realiza disparos automaticamente, variando o ângulo e a força dos projéteis.

Além dos disparos convencionais, cada lado conta com uma catapulta que lança uma bola de fogo especial. O jogo apresenta indicadores de vida, efeitos visuais e sonoros de disparo e explosão, e uma tela de resultado ao final da partida.

## Ferramenta utilizada

- **Engine:** GDevelop 5.
- **Versão identificada no projeto:** GDevelop 5.6.0 (build 287).
- **Tipo de projeto:** jogo 2D com lógica implementada pelo sistema visual de eventos do GDevelop.
- **Resolução configurada:** 1280 × 720 pixels, orientação paisagem.

Site oficial: [https://gdevelop.io/pt-br/download](https://gdevelop.io/pt-br/download)

## Controles

| Tecla | Ação |
|---|---|
| **Seta para cima** | Aumenta o ângulo do canhão do jogador. |
| **Seta para baixo** | Diminui o ângulo do canhão do jogador. |
| **Espaço (manter pressionado)** | Carrega a potência do disparo. |
| **Espaço (soltar)** | Dispara a bala de canhão com a potência acumulada. |
| **F** | Dispara a bola de fogo especial quando a catapulta estiver pronta. A habilidade possui recarga de 5 segundos. |
| **P** | Pausa ou retoma a partida. |

Quando uma das fortalezas perde toda a vida, o jogo exibe o resultado. O botão **Reiniciar** permite iniciar uma nova partida.

## Instalação e execução

1. Baixe o arquivo ZIP do projeto e extraia todo o seu conteúdo para uma pasta no computador.
2. Mantenha o arquivo `DueloDeCanhoes.json` e a pasta `assets` juntos, dentro da mesma pasta do projeto. Não mova nem renomeie os arquivos de recursos, pois o projeto utiliza caminhos relativos para localizar imagens, fontes e sons.
3. Instale e abra o **GDevelop 5**. O instalador está disponível no [site oficial do GDevelop](https://gdevelop.io/pt-br/download).
4. No GDevelop, escolha a opção para abrir um projeto existente e selecione o arquivo `DueloDeCanhoes.json` extraído no primeiro passo.
5. Com o projeto aberto, clique em **Pré-visualizar (Preview)** na barra superior do GDevelop para iniciar o jogo.
6. Para editar o jogo, utilize o gerenciador de projetos e os eventos disponíveis nas cenas `Menu` e `Batalha`.

O projeto utiliza as extensões `PanelSpriteButton` e `CameraShake`. Caso o GDevelop solicite a instalação ou atualização dessas extensões ao abrir o projeto, confirme a operação.

## Versão executável ou link jogável

O pacote disponibilizado contém o **projeto-fonte editável do GDevelop**. Ele não inclui um executável independente (por exemplo, `.exe`) nem uma versão publicada na internet com link jogável.

Para testar a versão incluída nesta entrega, abra o projeto no GDevelop e utilize a opção **Pré-visualizar (Preview)**, conforme descrito na seção anterior. Um executável ou link público poderá ser acrescentado a esta seção depois que o jogo for exportado ou publicado.

## Estrutura principal do projeto

```text
DueloDeCanhoes/
├── DueloDeCanhoes.json
├── README.md
└── assets/
    ├── imagens e sprites do jogo
    ├── fontes
    └── arquivos de áudio
```
