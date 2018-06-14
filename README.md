# TCC
TCC realizado para o curso de Engenharia de Computação na UNIVALI;

## Tema
Implementação e análise comparativa de algoritmos de Detecção de Atividade de Voz (VAD) em DSP

## Área
Sistemas Embarcados

## Algoritmos considerados
* VAD do Codec G.729 (G.729AB)
* Detector baseado na energia do sinal (Energy Based Detector - EBD)
* Detector baseado na energia e cruzamentos por zero (Zero Crossing Detector - ZCD).

## Contato
engronaldoab@gmail.com

## Referência

BORGES, Ronaldo Antunes. Implementação e comparação de algoritmos de Detecção de Atividade de Voz (VAD) em DSP. São José, 2008. 75 f. Trabalho de Conclusão de Curso (Graduação em Engenharia de Computação) - Centro de Ciências Tecnológicas da Terra e do Mar, Universidade do Vale do Itajaí, São José, 2008.

## Resumo
Durante uma conversação telefônica, cerca de 60% do tempo o canal fica inativo, isto é, o usuário não está falando. O algoritmo de detecção de atividade de voz (VAD - Voice Activity Detector) faz a distinção entre voz (atividade de voz) e silêncio ou ruído (inatividade de voz) possibilitando aos CODECs que fazem uso do VAD ter uma maior taxa de compressão quando inatividade de voz for detectada. Devido a dificuldade na correta distinção entre atividade e inatividade de voz, vários algoritmos VAD foram propostos. Neste trabalho foi realizada a implementação de três algoritmos VAD, em linguagem assembly do Processador Digital de Sinais (DSP) TMS320C5410 da Texas Instruments. Posteriormente também foi efetuada uma comparação entre as implementações em assembly onde foram consideradas três características: ocupação de memória, complexidade computacional (mipagem) e desempenho. Os algoritmos analisados foram: Detector baseado na energia do sinal (DBE), Zero Crossing Detector (ZCD), VAD do CODEC G.729 anexo B. O algoritmo EBD é o que apresentou a menor ocupação de memória e mipagem e ficou em segundo lugar em se tratando de alarmes-falsos. O ZCD ficou em segundo lugar levando-se em consideração a ocupação de memória e mipagem e teve maior taxa de alarmes-falsos. O VAD do G.729B é o algoritmo mais robusto dos considerados neste trabalho, apresentando a maior ocupação de memória, mipagem e melhor desempenho na distinção correta entre atividade e inatividade de voz.
