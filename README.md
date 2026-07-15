# Mesa de Corte a Plasma CNC

Projeto de uma mesa de corte a plasma desmontável, desenvolvida para o corte de chapas metálicas de grandes dimensões com boa precisão, baixo custo estrutural e facilidade de transporte/montagem.

O equipamento foi projetado e simulado em computador a partir dos requisitos do cliente, com foco em uma estrutura leve, modular e adaptável para diferentes tipos de serviço.

![Modelo 3D do conjunto de movimentação e tocha](Midia/Modelo 3d.png)
![Modelo 3D do conjunto de movimentação e tocha](docs/images/detalhe-carro-e-tocha.jpg)

## Visão geral

- Área de trabalho planejada para chapas de até **3 m x 2 m**.
- Corte de chapas de aço de até **1/2 polegada** de espessura.
- Capacidade para recortes complexos, bordas, entradas, divisões de chapas e cortes de grandes dimensões.
- Estrutura desmontável, leve e de fácil remontagem no local de uso.
- Projeto personalizado para atender necessidades específicas, incluindo cortes e furações em tubos.
- Controle compacto para facilitar instalação, manutenção e transporte.

## Estrutura mecânica

A estrutura utiliza uma solução simples e robusta, com guias construídas a partir de cantoneiras. Essa escolha reduz o custo de fabricação sem abrir mão do alinhamento necessário para obter boa precisão nos movimentos.

![Detalhe da guia com cantoneira e rolamentos](docs/images/detalhe-guia-cantoneira.jpg)

O conjunto foi pensado para ser desmontável. Isso facilita o transporte da máquina e permite que ela seja remontada conforme a necessidade do local de trabalho.

## Grelha e apoio das peças

A mesa possui grelha removível, permitindo adaptar o apoio do material de acordo com o tipo de peça. Quando necessário, a grelha pode ser retirada para acomodar peças inteiras ou materiais com altura maior, apoiando-os diretamente no chão.

Também foram previstos suportes de encosto para alinhamento dos dois lados da mesa, ajudando no posicionamento das chapas e peças durante o corte.

## Tração e movimentação

O sistema de movimentação utiliza correias dentadas com alma de aço. Como o conjunto móvel tem baixa inércia, a máquina consegue atingir boas velocidades em deslocamentos sem corte, mantendo uma construção mecânica relativamente simples.

## Aplicações

Este projeto pode ser usado como base para:

- corte CNC de chapas metálicas;
- preparação de peças para serralheria e caldeiraria;
- recortes personalizados em aço;
- cortes de grandes formatos;
- adaptações para corte e furação em tubos;
- estudos de estrutura, guias, tração e controle para máquinas CNC de plasma.

## Arquivos do projeto

O repositório contém arquivos de montagem e componentes em formato SolidWorks:

- `Mesa de corte a plasma.SLDASM`
- `SBR20 Linear Rail 2000 mm v7.SLDASM`
- `SBR bearing block resizable_SBR20.sldprt`
- `Peça7.SLDPRT`
- `Peça9.SLDPRT`
- pasta `Componentes/`

> Observação: alguns arquivos temporários do SolidWorks (`~$...`) também aparecem no repositório. Eles normalmente são gerados automaticamente durante a edição dos modelos.

## Referência em vídeo

O funcionamento e as características gerais da máquina foram descritos no vídeo:

[Mesa de corte a plasma - vídeo de referência](https://www.youtube.com/watch?v=QTmyu3U88S4)

Pontos destacados no vídeo:

- capacidade para chapas de 3 m x 2 m;
- corte de chapas de até 1/2";
- boa qualidade em recortes e formatos complexos;
- desenvolvimento simulado em computador;
- estrutura leve e desmontável;
- grelha removível para maior versatilidade;
- guias em cantoneira para reduzir custo mantendo alinhamento;
- tração por correias dentadas com alma de aço;
- conjunto de controle compacto.

## Status

Projeto mecânico em desenvolvimento/testes, com montagem provisória e validações iniciais apresentando bons resultados.
