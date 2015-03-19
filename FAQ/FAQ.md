#Sejam bem vindos ao Ciência Hacker!  
*Neste arquivo você encontrará algumas perguntas e respostas frequentes.*

* Grupo FB > https://www.fb.com/groups/cienciahacker
* Página > https://www.fb.com/CienciaHacker
* Youtube > www.youtube.com/cienciahacker
* Vimeo > www.vimeo.com/cienciahacker

```sh
Ementa  
        1) - Dicas de perguntas  
        2) - Perguntas e respostas frequentes  
                2.1     –     Por onde começar?  
                2.2     –     Como invadir/derrubar um site?  
                2.3     –     Como invadir redes WI-FI  
                2.4     –     Como quebrar senhas (hashes)  
                2.5     –     Posso hackear utilizando o Android?  
                2.6     –     Como hackear Facebook?  
                2.7     –     Me hackearam! O que fazer?  
                2.8     –     Como camuflar o IP?  
                2.9     –     Como camuflar o endereço MAC  
                2.10    –     Duvidas sobre Deep Web e como navegar  
                2.11    –     Programação. Como começar?  
                2,12    –     Preciso do Kali para poder realizar testes de penetração?  
                2.13    –     Backtrack ou Kali?  
                2.14    –     Qual o melhor Linux?  
        3) - Links mais pedidos  
                Wordlist  
                Kali Linux  
                Back|Track  
 ```
## 1. Dicas de Perguntas  
######*1. - Antes de começarmos, irei apresentar algumas dicas de como formular perguntas de forma adequada.*

------------------------------------------------------------------------------
######*1.1 - Não iremos fazer o trabalho de vocês, portanto não postem exercícios de faculdade e esperem aprovação ou respostas.*
------------------------------------------------------------------------------

######*1.2 - Na hora de formular perguntas tente ser o mais objetivo, breve e detalhista possível. As pessoas não gostam de ler textos imensos e muito menos não entender o que o autor quis dizer ao final deles.*
------------------------------------------------------------------------------
## 2. Perguntas e respostas
#####2.1 - Sou iniciante neste mundo, por onde começar?
 
R: Tudo depende de seu intuito uma vez que a palavra "hackear" é muito
genérica. Hackear pode ir desde invasão de sites até modificação de kernels
para funcionamento em arquiteturas diferentes das quais foram projetadas. Ache
um objetivo e mantenha o foco.
 
--------------------------------------------------------------------------------
#####2.2 - Como invadir/derrubar um site?
 
R: Não existe mistério. Para que você possa assumir o controle de um servidor ou
serviço é necessário que o mesmo apresente algumas falha ou vulnerabilidade.  
 
Para descobrir estas vulnerabilidades você pode fazer uso de softwares ou
testar por sí mesmo. Uma vez descoberta a(s) falha(s) é só explorar.  
 
Scanners de Vulnerabilidade: Acunetix, Vega, W3AF, Nessus, WPScan, Nmap  
 
Brinde: Servidores Apache até a versão 2.2.26 são vulneráveis a ataque DDoS
na sétima camada. Utilize a ferramenta Slowloris.pl (google it)

***VIDEO AULA > http://youtu.be/4oAmUnnSwJs?list=UUZPg5KlsbPsbxX3YQ_y_kRQ***

------------------------------------------------------------------------------
#####2.3 - Como invadir redes WI-FI  
 
As ferramentas mais famosas para estas tarefas são: Reaver e Aircrack-ng. Dê
uma pesquisada sobre elas.
 
------------------------------------------------------------------------------
#####2.4 - Como quebrar senhas (hashes)
 
R: Quebra de senhas é uma arte vai muito além de programas, porém sem
programas o processo seria infinitamente mais demorado.
Vocês podem utilizar o google, sites especializados, e ferramentas com foco
no cracking(quebra) de senhas.  
 
Ferramentas: John The Ripper, Hashcat, hash-identifier, findmyhash  

***VIDEO AULA > http://youtu.be/N7kR0ttcrxY?list=UUZPg5KlsbPsbxX3YQ_y_kRQ***

------------------------------------------------------------------------------
#####2.5 - Posso hackear utilizando o Android?  
 
Os Smartphones, por mais avançados que sejam, ainda são muito limitados e
por isso mesmo que existam programas para estes fins (hackear wifi por
exemplo), ele não funcionará corretamente uma vez que seu celular não possui
um chipset wireless (placa de rede) que de suporte a esta tarefa.  
 
------------------------------------------------------------------------------
#####2.6 - Como hackear Facebook?  
 
R: NÃO ensinamos a hackear facebook e não aprovamos perguntas como esta.
o mundo hacker é muito maior que isso. Porém certo dia acordamos felizes e de
bem com a vida, foi quando nosso canal enviou um vídeo sobre este assunto.
Mas que fique claro que esta foi um EXCESSÃO.  

***VIDEO AULA > http://youtu.be/37Sgx5r94kM?list=UUZPg5KlsbPsbxX3YQ_y_kRQ***

------------------------------------------------------------------------------
#####2.7 - Me hackearam no (face, gmail, lol, caralho a 4), me ajudem!  
 
R: Busque ajuda com o provedor do serviço  
 
------------------------------------------------------------------------------
#####2.8 - Como camuflar o IP  
 
R: Procure a utilização de uma VPN ou proxy free. Para a utilização de uma
VPN, recomendamos o Cyberghost ou SecurityKiss pelo fato de não guardarem
informações como sites acessados, tempo de conexão, etc. Lembre-se de ler o
contrato de prestação de serviço antes de utilizar.  
Eu em particular acho que o melhor método de anonimato ainda é a rede TOR.  
 
######Lista de Proxy Free:  
*http://www.proxy4free.com/list/webproxy1.html*  
**proxylist.hidemyass.com/**

***VIDEO AULA > http://youtu.be/v39VYpjJDK8?list=UUZPg5KlsbPsbxX3YQ_y_kRQ***

------------------------------------------------------------------------------
#####2.9 - Como camuflar o endereço MAC  
 
R: No linux basta utilizar o macchanger.  
Windows utilizem o Tmac  

***VIDEO AULA > http://youtu.be/54-M57HWA6w?list=UUZPg5KIsbPsbxX3YQ_y_kRQ***

------------------------------------------------------------------------------
#####2.10 - Duvidas sobre Deep Web e como navegar  
 
***Link:https://docs.google.com/document/d/1wZXvpL5EEDKiznAvHrMACFE7SM14t0SsX-cUlZZow2Y/edit**-
 
------------------------------------------------------------------------------
#####2.11 - Programação. Como começar?  

R: Caso esteja em dúvida sobre qual linguagem escolher, olhe alguns códigos de
diferentes linguagens e veja qual lhe parece mais simpática e lhe agrada mais.  
Feito isso, vá até o link a seguir e verifique os sites que possuem material sobre programação
da linguagem escolhida por você.  
 
***Link: http://pastebin.com/6UWaP7zN***
 
------------------------------------------------------------------------------
#####2.12 - Preciso do Kali para poder realizar testes de penetração?  
 
R: Não. Você pode realizar testes de penetração em toda e qualquer distribuição Linux
e até mesmo no ambiente Windows  
 
------------------------------------------------------------------------------
#####2.13 - Backtrack ou Kali?  
 
R: Kali linux é o sucessor do Backtrack, por isso dê preferencia ao Kali uma vez que ele conta com kernel e ferramentas atualizados.
 
------------------------------------------------------------------------------
#####2.14 - Qual o melhor Linux?  
 
R: A definição de melhor distro é subjetiva pois depende do propósito do usuário e do desempenho do computador do usuário.  

Certamente seu propósito é hacking e, falando superficialmente, qualquer distro pode ser útil com hacking, basta você saber armá-las; adicionar outro repositório ao sistema de pacotes etc., mas se o desempenho de seu computador for baixo, terá que procurar algo mais específico ou pelo menos uma interface específica dentro da distro escolhida.  
 
Falando de Kali e Parrot, para mim, eles não são muito diferentes, a diferença é questão de facilidade ou até vaidade.  
 
Se Platão conhecesse linux, ele diria que a melhor distro está somente no campo das ideias (a distro ideal) e as que podemos usar são somente cópias imperfeitas e subjetivas da perfeita, logo não existe a melhor distro.  
 

# 3. Links Mais pedidos
--------------------------
Wordlist = **http://hashkiller.co.uk/downloads.aspx**  
Kali Linux = **http://www.kali.org/downloads/**  
Back|Track =(32 bits) **https://thepiratebay.se/torrent/7529596/BackTrack_5_R3_Gnome_32bit**  
            (64 bits) **https://thepiratebay.se/torrent/7529601/BackTrack_5_R3_Gnome_64bit**  
```
