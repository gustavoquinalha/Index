# Sejam bem vindos ao Ciência Hacker!  
*Neste arquivo você encontrará algumas perguntas e respostas frequentes.*

**Ementa:**  
* 1) [Dicas de perguntas](#dicas-de-perguntas)  
* 2) [Perguntas frequentes](#perguntas-frequentes)  
    * 2.01. Por onde começar?  
    * 2.02. Como invadir/derrubar um site?  
    * 2.03. Como invadir redes WI-FI  
    * 2.04. Como quebrar senhas?
    * 2.05. Posso hackear utilizando o Android?  
    * 2.06. Como hackear Facebook?  
    * 2.07. Me hackearam! O que fazer?  
    * 2.08. Como camuflar o IP?  
    * 2.09. Como camuflar o endereço MAC?  
    * 2.10. Como navegar na Deep Web?
    * 2.11. Programação. Como começar?  
    * 2.12. Preciso do Kali para poder realizar testes de penetração?  
    * 2.13. Backtrack ou Kali?  
    * 2.14. Qual o melhor Linux?  
* 3) [Links mais pedidos](#links-mais-pedidos)  
    * 3.1. Wordlist  
    * 3.2. Kali Linux  
    * 3.3. Back|Track  
 
## Dicas de Perguntas  

1 - Antes de começarmos, irei apresentar algumas dicas de como formular perguntas de forma adequada.

1.1 - Não iremos fazer o trabalho de vocês, portanto não postem exercícios de faculdade e esperem aprovação ou respostas.  

1.2 - Na hora de formular perguntas tente ser o mais objetivo, breve e detalhista possível. As pessoas não gostam de ler textos imensos e muito menos não entender o que o autor quis dizer ao final deles.

## Perguntas frequentes
##### 2.01 - Sou iniciante neste mundo, por onde começar?
 
R: Para dominar o "hacking" (nada mais é que um especialista em uma determinada área) é necessário foco no conhecimento, a ansiedade e a pressa é o grande problema da maioria que começa, atrapalhando todo aprendizado. Os conhecimentos que abrange um hacker relaciona no conhecimento máximo nas diversas área da tecnologia, pois a partir disso é possível explorar as vulnerabilidades nos ambientes presentes. Destacamos os estudos em:

Ethical Hacker: valores e conduta morais que o um "hacker" tem.

Redes: conhecimento de protocolos, endereçamentos, estrutura e topologias de rede. 

Sistemas operacionais: conhecimento máximo na maior quantidade de sistemas existentes como Linux(fundamental para mexer nas ferramentas) Windows e Mac.

Website/web-service: ter entendimento das plataformar webs, que recursos são usados no ambiente como linguagens, aplicações, redirecionamentos de DNS, entre outras informações

Tendo conhecimento nesses requisitos ficá fácil dominar qualquer conhecimento de técnicas de invasão. Lembre-se que o ethical hacking é o principal elemento de um "hacker" e jamais se esqueçam disso!

Deixo link para quem quiser ler um guia interessante de como começar, abordando a mesma visão mas de forma mais contextualizada.

https://linux.ime.usp.br/~rcaetano/docs/hacker-howto-pt.html
 
- - -
##### 2.02 - Como invadir/derrubar um site?
 
R: Umas das perguntas mais feita no nosso grupo e descartada devido a repetides dela. Para "derrubar ou invadir" qualquer alvo, necessita que você descubra alguma falha nele como exemplo fazer scanning no site/servidor procurando vulnerabilidade para explora-la, lembre que um site pode possuir falhas relacionado a sua aplicação (onde podemos explorar a falha derrubando o site com a ferramenta Slowloris), no banco de dados (invasão de site explorando a falha SQL injetcion), recursos e ferramentas do sistemas, como as falha encontradas em CMS (Joomla e Wordpress), entro outras milhares de formas.

Para descobrir estas vulnerabilidades você pode fazer uso de softwares (scanners) ou testar por si mesmo, como exemplo das ferramentas Acunetix, Vega, W3AF, Nessus, WPScan, Nmap.

*[VIDEO AULA](http://youtu.be/4oAmUnnSwJs?list=UUZPg5KlsbPsbxX3YQ_y_kRQ)*

- - -
##### 2.03 - Como invadir redes WI-FI  
 
As ferramentas mais famosas para estas tarefas são: Reaver ou Bully e Aircrack-ng. Dê uma pesquisada sobre elas.
 
- - -
##### 2.04 - Como quebrar senhas (hashes)
 
R: Para quebrar uma hash (senha cifrada) é necessário antes identificar o tipo da hash como Md5, Md4, Sha1, Des, entre outras. A identificação dela é fundamental para decifrar a senha, os meio mais utilizado é o brute force a qual ele verifica dentro uma lista de senhas qual é igual a ela. Podemos utilizar sites especializados, e ferramentas para fazer o processo deciframento.

Ferramentas: John The Ripper, Hashcat, hash-identifier, findmyhash.

[VIDEO AULA](http://youtu.be/N7kR0ttcrxY?list=UUZPg5KlsbPsbxX3YQ_y_kRQ)

[TUTORIAL](http://cienciahacker.com.br/identificando-tipos-de-hash)

- - -
##### 2.05 - Posso hackear utilizando o Android?  
 
Os Smartphones, por mais avançados que sejam, ainda são muito limitados e
por isso mesmo que existam programas para estes fins (hackear wifi por
exemplo), ele não funcionará corretamente uma vez que seu celular não possui
um chipset wireless (placa de rede) que dê suporte a esta tarefa.

Mas, hoje em dia, já é possível emular uma distribuição GNU/Linx por cima do Android. Pesquise sobre isso e seja feliz!
 
- - -
##### 2.06 - Como hackear Facebook?  
 
R: NÃO ensinamos a hackear facebook e não aprovamos perguntas como esta.
o mundo hacker é muito maior que isso. Porém certo dia acordamos felizes e de bem com a vida, foi quando nosso canal enviou um vídeo sobre este assunto.
Mas que fique claro que esta foi um EXCESSÃO.  

*[VIDEO AULA](https://youtu.be/37Sgx5r93kM)*

Não existe meio de invadir um Facebook de uma pessoa com um ataque direto, pois isso existe meio de invadi-lo persuadindo a pessoa que chamamos de Engenharia Social (que pode ser feito através de Keyloggers ou Pishing). Outro meio usado, mas apenas em rede interna é o Sniffer que captura senhas, exemplo da ferramenta Cain e Wireshark.

- - -
##### 2.07 - Me hackearam no (face, gmail, lol, caralho a 4), me ajudem!  
 
R: Busque ajuda com o provedor do serviço.
 
- - -
##### 2.08 - Como camuflar o IP? Como ficar anonimo e seguro na rede?

R: Para camuflar IP (que nada mais é um processo de você obter um novo IP sobre outro servidor) existe serviços de VPN ou Proxy. Para maior segurança recomendamos a utilização de uma VPN devido a criptografia da sua conexão com servidor deles, garantindo maior segurança durante a navegação de seus dados. Recomendamos o Cyberghost ou SecurityKiss pelo fato de não guardarem informações como sites acessados, tempo de conexão, etc. Lembre-se de ler o contrato de prestação de serviço antes de utilizar.

Outros meio que recomendamos é usar utilizar o Whonix, que usa a rede TOR como gateway na rede. Tendo anonimato devido a criptografia que ele faz na rede, e possui ferramenta embutida no Whonix como firewall.

[VIDEO AULA 1](https://www.youtube.com/watch?v=0isHTWPt-tE)

[VIDEO AULA 2](https://www.youtube.com/watch?v=XCdz7lUUazY)

[TUTORIAL 1](http://cienciahacker.com.br/windows-10-adicionando-proxies-garantindo-o-anonimato-basico/)

[TUTORIAL 2](http://cienciahacker.com.br/instalando-e-usando-o-proxychains/)

###### Lista de Proxy Free:  
* http://www.proxy4free.com/list/webproxy1.html
* http://proxylist.hidemyass.com/

*[VIDEO AULA](http://youtu.be/v39VYpjJDK8?list=UUZPg5KlsbPsbxX3YQ_y_kRQ)*

- - -
##### 2.09 - Como camuflar o endereço MAC  
 
R: A importância de camuflar o MAC Address é para não rastrear sua placa de rede, assim fazem no endereço IP. No Linux basta utilizar o macchanger e no Windows utilizem a ferramenta Tmac.

*[VIDEO AULA](http://youtu.be/54-M57HWA6w?list=UUZPg5KIsbPsbxX3YQ_y_kRQ)*

- - -
##### 2.10 - Duvidas sobre Deep Web e como navegar  
 
*[Leia a apostila](faq-deepweb.md)*
 
- - -
##### 2.11 - Programação. Como começar?  

R: Caso esteja em dúvida sobre qual linguagem escolher, olhe alguns códigos de diferentes linguagens e veja qual lhe parece mais simpática e lhe agrada mais.

Feito isso, vá até o link a seguir e verifique os sites que possuem material sobre programação da linguagem escolhida por você.  
 
*[Compilado de Programação](programação.md)*
 
- - -
##### 2.12 - Preciso do Kali para poder realizar testes de penetração?  
 
R: Não. Você pode realizar testes de penetração em toda e qualquer distribuição Linuxe até mesmo no ambiente Windows.
 
- - -
##### 2.13 - Backtrack ou Kali?  
 
R: Kali linux é o sucessor do Backtrack, por isso dê preferencia ao Kali uma vez que ele conta com kernel e ferramentas atualizados.
 
- - -
##### 2.14 - Qual o melhor Linux?
 
R: A definição de melhor distro é subjetiva pois depende do propósito do usuário e do desempenho do computador do usuário.  

Certamente seu propósito é hacking e, falando superficialmente, qualquer distro pode ser útil com hacking, basta você saber armá-las; adicionar outro repositório ao sistema de pacotes etc., mas se o desempenho de seu computador for baixo, terá que procurar algo mais específico ou pelo menos uma interface específica dentro da distro escolhida.  
 
Falando de Kali e Parrot, para mim, eles não são muito diferentes, a diferença é questão de facilidade ou até vaidade.  
 
Se Platão conhecesse Linux, ele diria que a melhor distro está somente no campo das ideias (a distro ideal) e as que podemos usar são somente cópias imperfeitas e subjetivas da perfeita, logo não existe a melhor distro.  

Se quiser ver uma lista de distribuições GNU/Linux e algumas informações sobre elas, fique a vontade para visitar o [Distro Watch](http://distrowatch.com/index.php?language=PT).
 

## Links mais pedidos
- - -

##### Wordlist

- http://cienciahacker.com.br/downloads/wordlists/
- http://hashkiller.co.uk/downloads.aspx  
- https://downloads.skullsecurity.org/passwords/  

#### Kali Linux

- http://www.kali.org/downloads/ 

#### Back|Track

- (32 bits) https://thepiratebay.se/torrent/7529596/BackTrack_5_R3_Gnome_32bit
- (64 bits) https://thepiratebay.se/torrent/7529601/BackTrack_5_R3_Gnome_64bit  
```
