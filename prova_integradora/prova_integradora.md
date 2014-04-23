---
geometry:
    - margin=1in
author:
    - Filipe Fernandes
date:
    - '23-Abril-2014'
title:
    - Prova Integradora
header-includes:
    - \usepackage{fancyhdr}
    - \pagestyle{fancy}
    - \fancyhead[CO,CE]{}
    - \fancyfoot[CO,CE]{}
    - \fancyfoot[LE,RO]{\thepage}
...


## Questões de Oceanografia Física Dinâmica

1. Você foi escolhido para planejar um cruzeiro saindo de *Cape Cod-MA* até
   *Bermuda*.  Usando o seu conhecimento sobre Geostrofia indique o sentido dos
   giros e/ou correntes nos pontos **A** e **B** e trace a rota mais
   eficiente (ou seja, aproveitando as correntes oceânicas) saindo do ponto
   vermelho em direção ao ponto verde.

   (Sua resposta deve conter onde estão as Alta e Baixa pressões e como elas se
   balançam com a Força de Coriolis: ou seja o caminho que te leva a traçar as
   correntes.)

![Temperatura Superficial da Mar na região da Corrente do Golfo.](./figures/gs_02jun13.png)


\newpage

2. Observe o anel (ou vórtice) da Corrente Norte do Brasil (*NBC Ring*) na
   figura abaixo e responda:

    a) Por que a concentração de Clorofila (Cla) é baixa no centro do vórtice?
       (Dica: Faça uma análise da provavél temperatura superficial para a alta
        e baixa concentração de Cla.)

    b) Como seria o **gradiente de pressão** entre um ponto da borda (alta
       concentração Cla) até o centro (baixa de concentração de Cla) do
       vórtice?  Trace o balanço de Forças que mantém esse vórtice.

    c) Porque há uma aumento na concentração de Cla mais ao norte
       ($\sim 10^{\circ}$ N)

![Concentração de Clorofila na região da Corrente Norte do Brasil.](figures/NBC.png)

\newpage

3. Avalie Coriolis no plano-$f$ (ou seja, centrado em uma latitude) para:

    a) $f_o = 0^{\circ}$S,
    b) $f_o = 30^{\circ}$S, e
    c) $f_o = 90^{\circ}$S.

    Use: $f_o = 2\Omega\sin\theta$, onde $\theta$ é a latitude em radianos e
    $\Omega = 7.292 \times 10^{-5}$ rad s$^{-1}$.

    Agora calcule o período inercial T$_{i} = \dfrac{2\pi}{f_o}$ para cada um e
    discuta o resultado.  (Dica: converta T$_{i}$ para horas.)

<!--
pandoc --smart --normalize --standalone \
       --variable geometry:margin=1in \
       --from markdown prova_integradora.md \
       --to latex \
       --latex-engine=xelatex \
       --output prova_integradora.pdf
-->

<!--
pandoc --smart --normalize --standalone \
       --from markdown prova_integradora.md \
       --to docx \
       --output prova_integradora.docx
-->
