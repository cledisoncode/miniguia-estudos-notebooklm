# miniguia-estudos-notebooklm
Um guia de estudos redes de computadores criado com o notebooklm.

Eu escolhi Fundamentos de Redes de Computadores, uma matéria da faculdade, que estou estudando esse semestre e que mesmo tendo o material disponibilizado pela faculdade, não estava conseguindo compreender a matéria, por isso resolvi que esse seria um dos meus primeiros cadernos temáticos do noteboolm. Pelo fato dessa ia conseguir gerar resumos,
vídeos, questões e mapa mentais,meu principal objetivo foi utilizar dessas possibilidades para testar o que eu já sabia do assunto, entender e absorver o que eu ainda tinha dúvida tanto para a prova, quanto para meu conhecimento futuro.

FONTES:<br>
.Pdf's que cada tema da matéria possui;
.vídeos do curso de redes de computadores do professor Gustavo Guanabara:<br>
https://www.youtube.com/watch?v=q65kHIvtWxg&list=PLHz_AreHm4dkd4lr9G0Up-W-YaHYdTDuP&index=8&pp=iAQB0gcJCSgLAYcqIYzv;
https://www.youtube.com/watch?v=ee5htpGdWHY&list=PLHz_AreHm4dkd4lr9G0Up-W-YaHYdTDuP&index=9&pp=iAQB0gcJCSgLAYcqIYzv;
https://www.youtube.com/watch?v=_826vVEokj8&list=PLHz_AreHm4dkd4lr9G0Up-W-YaHYdTDuP&index=6&pp=iAQB


ENGENHARIA DE PROMPTS:

PRIMEIRO PROMPT: " então preciso que você selecione os assuntos mais abordados nas provas de redes de computadores e também faça um resumo claro e focado nas perguntas que mais caem nessas provas de redes de computadores".

RESPOSTA:<br>

"" 1. Modelos de Referência: OSI vs. TCP/IP
    Este é o assunto mais básico e obrigatório. As provas costumam cobrar a ordem das camadas e a diferença de funções entre elas.
    Modelo OSI (7 camadas): É um modelo de referência teórico
    . A ordem (de cima para baixo) é: Aplicação, Apresentação, Sessão, Transporte, Rede, Enlace e Física
    .
    Modelo TCP/IP (4 ou 5 camadas): É a arquitetura real da internet
    . Diferente do OSI, ele aglutina as funções de Apresentação e Sessão na camada de Aplicação
    .
    Elementos da Camada:
    Serviço: O que a camada faz
    .
    Protocolo: Como a camada faz (regras e implementação)
    .
    Interface: Ponto de comunicação entre camadas adjacentes
    .
  2. Encapsulamento e PDUs (Protocol Data Units)
    Questões clássicas pedem para identificar o nome do dado em cada camada durante o processo de encapsulamento (quando o dado desce na origem, ganhando cabeçalhos)
    .
    Aplicação: Mensagem
    .
    Transporte: Segmento (no TCP) ou Datagrama de Usuário (no UDP)
    .
    Rede: Datagrama ou Pacote
    .
    Enlace: Quadro (ou Frame)
    .
    Física: Bits
    .
  3. Camada de Transporte: TCP vs. UDP
    A comparação entre esses dois protocolos é um dos temas preferidos das bancas
    .
    TCP (Transmission Control Protocol):
    Orientado à conexão: Utiliza o three-way handshake (SYN, SYN-ACK, ACK) para estabelecer conexão
    .
    Confiável: Garante a entrega, a ordem dos dados e faz controle de erros, fluxo e congestionamento
    .
    Uso: Web (HTTP), E-mail (SMTP), Transferência de arquivos (FTP)
    .
    UDP (User Datagram Protocol):
    Não orientado à conexão: Envia dados sem aviso prévio ("melhor esforço")
    .
    Rápido: Sem o overhead de confirmações, ideal para aplicações que toleram perdas mas não atrasos
    .
    Uso: Streaming de vídeo/áudio, VoIP, consultas DNS
    .
  4. Camada de Rede: Endereçamento e Protocolos de Controle
    Foque em como os dados encontram o caminho e como os endereços são geridos.
    IPv4 vs. IPv6: O IPv4 tem 32 bits; o IPv6 tem 128 bits (criado para resolver a escassez de endereços)
    .
    CIDR e Máscaras: O prefixo (ex: /24) determina qual parte do endereço identifica a rede e qual identifica o hospedeiro
    .
    NAT (Network Address Translation): Permite que vários dispositivos usem um único endereço IP público, traduzindo endereços privados internos
    .
    Protocolos Auxiliares:
    ARP: Descobre o endereço físico (MAC) a partir de um endereço IP conhecido
    .
    DHCP: Atribui endereços IP de forma automática e dinâmica aos dispositivos
    .
    ICMP: Utilizado para relatar erros e sinais de controle (base do comando ping)
    .
  5. Camada de Enlace e Dispositivos
    As provas costumam testar se você sabe em qual camada cada equipamento opera
    .
    Roteador: Opera na Camada 3 (Rede). Decide o melhor caminho para o pacote (roteamento)
    .
    Switch: Opera na Camada 2 (Enlace). Encaminha quadros baseado no endereço físico (MAC)
    .
    Controle de Acesso ao Meio (MAC): Protocolos como CSMA/CD (usado na Ethernet para detectar colisões) e ALOHA (permite colisões, mas requer retransmissão) são temas comuns
    .
    6. Segurança da Informação (Tríade CID)
    Muitas questões focam nos princípios básicos e tipos de ataques
    .
    Tríade CID:
    Confidencialidade: Sigilo dos dados (somente autorizados acessam)
    .
    Integridade: Garantia de que a informação não foi alterada
    .
    Disponibilidade: Acesso garantido quando necessário
    .
    Ataques:
    Passivos: Apenas interceptam dados (atacam a confidencialidade)
    .
    Ativos: Tentam alterar recursos ou afetar a operação (interrupção, modificação, personificação)
    .
    Dica para a prova: Sempre que ler sobre "entrega confiável processo a processo", pense em TCP (Transporte)
    . Se a questão falar em "roteamento" ou "entrega host a host", a resposta é Camada de Rede
    . Se falar em "bits em quadros" ou "nó a nó", é Camada de Enlace  
""

ANÁLISE DA RESPOSTA RECEBIDA:<br>
A primeira coisa que eu solicitei para a ia foi uma análise dos assuntos que mais aparecem nas questões de redes de computadores e fazer um resumo, ela me apresentou somente 6 tópicos de assuntos de redes, eu não havia especificado a qauntidade. O resumo foi bem direto e claro e muito bem explicativo, com eles eu  conseguir entender melhor algumas dúvidas que antes eu tinha principlamente sobre a Camada de Rede.

SEGUNDO PROMPT: "faça 10 perguntas baseadas nos tópicos que você me apresentou"

RESPOSTA:<br>
  "" Com base nos temas essenciais de redes de computadores discutidos e no material fornecido, aqui estão 10 perguntas fundamentais para o seu estudo, focadas no que costuma ser cobrado em provas:
  Perguntas de Revisão
  1.Modelos de Referência: Quantas camadas possui o modelo OSI e qual camada da arquitetura TCP/IP absorve as funções de Apresentação e Sessão?<br>
  2.Encapsulamento: Qual é o nome técnico dado à Unidade de Dados de Protocolo (PDU) quando a informação está na camada de Transporte e na camada de Rede?<br>
  3.Transporte (TCP vs. UDP): Qual é a principal diferença entre o protocolo TCP e o UDP em termos de confiabilidade e estabelecimento de conexão?<br>
  4.Protocolo ARP: Qual é a função do protocolo ARP (Address Resolution Protocol) dentro de uma rede local?<br>
  5.Protocolo DHCP: De que maneira o protocolo DHCP facilita o trabalho de um administrador de redes em ambientes com muitos dispositivos móveis?<br>
  6.Esgotamento de Endereços: O que é a técnica de NAT (Network Address Translation) e qual problema crítico da internet ela foi desenvolvida para mitigar?<br>
  7.Equipamentos de Rede: Em quais camadas do modelo de referência operam, respectivamente, um Switch (comutador) e um Roteador?<br>
  8.Endereçamento IP: Qual é o tamanho, em bits, de um endereço IPv4 comparado a um endereço IPv6?<br>
  9.Segurança da Informação: Defina as propriedades de Confidencialidade, Integridade e Disponibilidade (Tríade CID).<br>
  10.Tipos de Ataques: Qual é a diferença fundamental entre um ataque passivo (como a interceptação) e um ataque ativo (como a modificação)?<br>

  ""

ANÁLISE DA RESPOSTA RECEBIDA:<br>
DIFICULDADE COM AS PERGUNTAS
A segunda coisa que eu pedi foi pra ela fazer perguntas baseadas no resumo que ela me apresentou, só que dessa vez eu especifiquei uma quantidade exata, eu percebi que as perguntas que ela faz são voltadas mais para fazer a pessoa decorar, eu estava esperando perguntas baseadas em situações problemas, então no terceiro prompt, eu especifiquei o tipo de pergunta que eu gostaria.




