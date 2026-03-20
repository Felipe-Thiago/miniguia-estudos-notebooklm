# Desafio "NotebookLM" - Felipe Thiago da Silva
Entrega do desafio para o estudo da ferramenta "NotebookLM", realizado durante o bootcamp de Cibersegurança Riachuelo na plataforma DIO 

## Contexto e Objetivos
A ideia deste miniguia é entender melhor sobre os eventos de "Capture a Bandeira" (CTF) realizados por entusiastas do hacktivismo como forma de preparo para o entendimento da variedade de ferramentas utilizadas pelos praticantes do hacking ético, assim como obter uma introdução ao tema de forma amigável e lúdica.

## Separação de fontes

- [Implementation and Trial Practices for Hacking Competition CTF
as Introductory Educational Experience
for Information Literacy and Security Learning](https://www.researchgate.net/profile/Natalie-Walker-15/publication/310753834_Proceedings_of_the_Fifth_International_Conference_on_Informatics_and_Applications_Takamatsu-Japan_2016/links/5835e29608ae74bb3aa25cff/Proceedings-of-the-Fifth-International-Conference-on-Informatics-and-Applications-Takamatsu-Japan-2016.pdf#page=59) 

- [What is CTF? An introduction to security Capture The Flag competitions](https://www.youtube.com/watch?v=8ev9ZX9J45A)

- [What is CTF - Hack The Box](https://www.hackthebox.com/blog/what-is-ctf)

- [The CTF Primer](https://primer.picoctf.org/)


## Testes de prompts
Para as fontes deste assunto, foi separado ao menos um vídeo, um artigo específico de uma edição inteira de uma revista de tecnologia, um site com uma introdução e abrangência do assunto em forma de "abas", e dois blogs com artigos completos e extensos sobre o tema, todos em inglês. Com base nessa variedade, o objetivo foi entender se a ferramenta tem a capacidade de ler os sites por completo tal como abstrair somente o necessário, quando requisitado. Também foi utilizada a opção de "Deep Research", aceitando 20 sugestões de fontes do próprio NotebookLM para composição da conversa.

Observação: Uma dificuldade encontrada foi de que alguns sites de aparente importância não conseguiram ser aceitos pelo leitor de fontes devido a um paywall ou a erros de leitura, de forma que a solução acabou sendo selecionar diferentes opções ou enviar para o Notebook o arquivo da página em forma de PDF salvo pela opção de impressão da página.

Para explorar mais sobre o assunto, foi realizada uma série de perguntas em que as respostas se encontram de forma resumida. Quanto a estas respostas - pela variedade de fontes utilizadas e pela natureza dos tópicos abordados -, pareceram satisfatórias e não necessitaram de reformulações ou novos pedidos. As próprias perguntas geradas pela IA também pareceram interessantes, de forma que agem como tópicos mais profundos ao ter interesse sobre um tema em específico, mas acabam tendo variações e especificidades muito grandes para serem abordadas.

### Perguntas estratégicas:
 - **O que é e como o capture the flag ajuda estudantes e entusiastas de cibersegurança?**  
   > **Resposta do NotebookLM**: O Capture The Flag (CTF) é uma competição de cibersegurança gamificada onde os participantes enfrentam desafios técnicos para encontrar uma "flag" — um código, arquivo ou token oculto que serve como prova de que uma vulnerabilidade foi explorada ou um problema foi resolvido. Essas competições simulam cenários de hacking do mundo real, exigindo que os participantes identifiquem falhas, explorem fraquezas e defendam sistemas em um ambiente controlado e ético.
   > As competições de CTF ajudam estudantes e entusiastas de diversas formas fundamentais:
   > 1. Desenvolvimento de Habilidades Técnicas Práticas
   > 2. Estímulo ao Pensamento Crítico e Criatividade
   > 3. Fortalecimento de Soft Skills
   > 4. Impacto na Carreira e Networking
   > 5. Acessibilidade e Ambiente Seguro

 - **Quais são as primeiras e principais ferramentas a se utilizar nesse tipo de atividade?**
   > **Resposta do NotebookLM**: Para começar nas atividades de Capture The Flag (CTF), o primeiro passo essencial é a configuração de um ambiente adequado, sendo o Kali Linux ou o Parrot OS as distribuições mais recomendadas por já virem com centenas de ferramentas de segurança pré-instaladas. É fundamental desenvolver fluência na linha de comando Linux e em utilitários básicos de navegação e manipulação de arquivos, como ls, cd, cat, grep e find.  
   > As principais ferramentas utilizadas são categorizadas de acordo com o tipo de desafio:
   > - Ferramentas de Uso Geral e Criptografia: CyberChef, John the Ripper, Hashcat
   > - Exploração Web: Burp Suite, Ferramentas de Desenvolvedor do Navegador (F12), SQLMap
   > - Engenharia Reversa e Exploração Binária (Pwn): Ghuidra, GDB + pwndbg/GEF, Python + pwntools
   > - Forense Digital e Análise de Rede: Wireshark, Volatility, Binwalk
   > - Linguagem de programação: Python
  
 - **Existe mais de um modelo deste desafio?**
  *Sugestão da própria IA:* **Quais são os principais tipos de competições de CTF?**
   > **Resposta do NotebookLM**: As competições de Capture The Flag (CTF) são classificadas principalmente por sua estrutura e dinâmica de jogo. De acordo com as fontes, os principais tipos são:
   > 1. Jeopardy-style (Estilo Jeopardy)
   > 2. Attack-Defense (Ataque e Defesa)
   > 3. King of the Hill (KotH)
   > 4. Formatos Mistos e Temáticos
   > 5. Wargames e Desafios Gamificados

 - **Quais são os principais conceitos de internet e redes a se aprender para começar com CTF?**
   > **Resposta do NotebookLM**: Para começar em competições de Capture The Flag (CTF), é fundamental compreender como os dados viajam pela internet e como os sistemas se comunicam em uma rede. O domínio desses conceitos permite analisar tráfego malicioso, identificar serviços abertos e explorar vulnerabilidades de rede.
   > Os principais conceitos de internet e redes a serem aprendidos incluem:
   > 1. O Modelo de Camadas (OSI e TCP/IP)
   > 2. Protocolos Essenciais e Serviços
   > 3. Mecanismos de Conexão e Tráfego
   > 4. Reconhecimento e Escaneamento de Rede

## Miniguia de Estudo
### Mapa mental 
![Mapa mental gerado pelo NotebookLM](https://raw.githubusercontent.com/Felipe-Thiago/miniguia-estudos-notebooklm/refs/heads/main/NotebookLM%20Mind%20Map.png)

### Glossário
- Formatos de competição: Jeopardy-style, Attack-Defense, King of the Hill, Wargames;
- Domínios Técnicos: Exploração Web, Engenharia Reversa, Exploração Binária, Criptografia e Forense Digital;
- Filosofia Hacker: Pensar de forma criativa e analítica para encontrar soluções não convencionais sob pressão de forma segura, legal e ética;
- Soft Skills: CTFs possuem trabalho em equipe e colaboração, além de comunicação eficiente através de relatórios write-ups

### Prompts para reutilizar
- Quais são as primeiras e principais ferramentas a se utilizar nesse tipo de atividade?
- Existe mais de um modelo deste desafio?
- Como posso configurar o Kali Linux para começar a praticar?
