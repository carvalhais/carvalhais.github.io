---
title: "PU7OLV"
date: 2023-06-20T14:20:29-03:00
author: "Paolo Oliveira"
---

Estação composta de 3 rtl-sdr, 1 hackrf, 1 JRC NRD-525g e vários softwares de
decodificação e propagação de sinais através da internet, sediada no município
de Fortaleza/CE no grid HI06sg, mantida por [Paolo Oliveira](https://paolo.zone)

## Link de acesso
A ser disponibilizado.

## Informações técnicas
| Parâmetro        | Detalhamento                                    |
|------------------|-------------------------------------------------|
| _Receptor_       | rtl-sdr v3 e hackRf                             |
| _Faixa de freq._ | 0.5 KHz a 30 MHz e 50Mhz a 1200 Mhz             |
| _Span máximo_    | 660 Khz                                         |
| _BW do canal_    | 15 KHz                                          |
| _Antena_         | Loop magnética, turnstile, dipolo e j-pole      |
| _Daemon_         | rtl-tcp                                         |
| _Sist. Oper._    | Ubuntu server 22.04.2 LTS                       |
| _Hardware_       | generico i5 com 8GB de RAM                      |
| _Grid_           | HI06sg                                          |

## Observações
Antenas Loop magnetica e j-polo instaladas em janelas de apartamento com
visão desobstruída da direção Europa e America central. Antena turnstile e
dipolo no terraço do predio. Ruido intermédiarion.

**Atenção**: o rádio definido por software não é acessível diretamente pelo
navegador, o acesso é feito de forma nativa através do software
[SDR#](https://airspy.com/download/), que deve ser previamente instalado no
computador do usuário.
