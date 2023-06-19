---
title: "PY2PLL"
date: 2023-06-18T21:35:00-03:00
author: "Marcus Ramos"
ShowBreadCrumbs: true
---

Utiliza plataforma Beaglebone, padrão para o KiWi SDR, acessível através de web 
browsers comuns, sediada no município de São Bernardo do Campo/SP, na altura do 
Km 27 da Via Anchieta. O equipamento é de propriedade do radioescuta Rudolf 
Grimm e compartilha antenas de recepção existentes na estação PY2PLL, através 
de divisor 1:4 ou 1:2. Durante os finais de semana a recepção pode ser 
interferida pois a estação participa de vários contestes ao longo do ano.

## Link de acesso
http://186.193.231.135:7999

## Informações técnicas
| Parâmetro        | Detalhamento                                    |
|------------------|-------------------------------------------------|
| _Receptor_       | KiWi SDR                                        |
| _Faixa de freq._ | 15 KHz a 30 MHz                                 |
| _Span máximo_    | 30 MHz                                          |
| _BW do canal_    | 15 KHz                                          |
| _Antena_         | Loop Magnética Ativa ou Mini Whip               |
| _Daemon_         | Proprietário                                    |
| _Sist. Oper._    | Debian 9                                        |
| _Hardware_       | Beaglebone Black (AM335x, Texas Instruments)    |

## Observações
Antena loop em rotor acima de laje, orientada para minimizar interferências dos 
imóveis existentes na vizinhança; apesar de estar localizada em zona rural, 
interferências sempre existem. Atualmente a mini whip encontra-se inativa, 
aguardando troca de cabo coaxial (65 metros). Com ela melhora bastante o 
desempenho de 15 a 500KHz (VLF/LF) permitindo a escuta de diversas estações 
nesse segmento.

**Atenção**: o uso do receptor está limitado a 2h/dia/IP de acesso, por 
solicitação do proprietário do hardware.

## Fotografias
_Fotografia da antena_:
![Fotografia da antena.](./antenna.jpg#center)
