---
Materia: Segurança da Informação
Assunto: Criptografia
Criação: 2024-12-08
EstudadoEm: 2024-09-16
tags:
  - mppr
Voltas: "0"
Nível: "0"
---
![[anki1.png| 30]]  
**Criptologia**: Estudo da Criptografia, da Criptoanálise e da Esteganografia.

  
![[Pasted image 20240729060901.png]]
 

**Esteganografia**  É o estudo e uso das técnicas para ocultar a existência de uma mensagem dentro de outra.

![[Pasted image 20240729060929.png]]

**Criptoanálise**  É a arte de tentar descobrir o texto cifrado e/ou a lógica utilizada em sua encriptação (chave).

![[Pasted image 20240729060955.png]]

**Criptografia**  “criptografia” do grego. Kruptós = “secreto” ou “oculto”, e graphía = “escrita”.  “escrita secreta”.  A criptografia, considerada como a ciência e a arte de escrever mensagens em forma cifrada ou em código.

Por meio do uso da criptografia você pode:  proteger os dados sigilosos armazenados em seu computador,  criar uma área (partição) específica no seu computador, onde os dados serão automaticamente criptografados.  proteger seus backups contra acesso indevido.  proteger as comunicações realizadas pela Internet. 

Ex: Transações bancárias e comerciais realizadas.

**O que se obtém com Criptografia:** 

Integridade  
Autenticidade 
Confidencialidade 
Não repúdio  
**Disponibilidade NUNCA!!!**
  

[https://www.tecconcursos.com.br/questoes/165152](https://www.tecconcursos.com.br/questoes/165152)

  

**Cifra de César**  

Cifra de substituição monoalfabética.

![[Pasted image 20240729061148.png]]

  

Cifra de César com alfabeto com rotação à esquerda de quatro posições:  

Alfabeto Normal: ABCDEFGHIJKLMNOPQRSTUVWXYZ  
Alfabeto Cifrado: EFGHIJKLMNOPQRSTUVWXYZABCD

  
**Esquemas de Cifração**  
Computacionalmente seguro
**Custo** => maior do que o valor das informações.  
**Tempo** => maior do que o tempo de vida útil da informação.  

  
**Incondicionalmente Seguro** 
Ex: One Time Pad (OTP) 
* Tamanho da chave secreta >= texto claro. 
* Deve ser utilizada somente uma vez.

**Classificação quanto às dimensões**  

Os sistemas criptográficos são genericamente classificados em três dimensões: 
 Operações usadas (**Substituição** ou **Transposição**) 
 Número de chaves (**simétrico** ou **assimétrico**)  
 Modo de processamento (**Cifra de Bloco** ou **Fluxo**)

**Classificação quanto às dimensões**

  Operações usadas (Substituição ou Transposição)
-   **Substituição**
 Cada elemento (bit, letra, grupo de bits ou letras) do texto claro é mapeado para um outro elemento (disfarce). 

Ex: cifra de César. **f  a  c  a** 
                             **c  d  f  d**  
                             
* ***Transposição (ou permutação)**

Os elementos do texto claro são rearranjados.

 Ex:          c r i p t o g r a f i a 
                **a p a g o r c i f t i r**

  [https://www.tecconcursos.com.br/questoes/441406](https://www.tecconcursos.com.br/questoes/441406)

  **Classificação quanto às dimensões** 

 A maioria dos sistemas, conhecidos como sistemas de produto, utilizam vários estágios de substituições e transposições. 

 Tem por fundamento que nenhuma informação seja perdida.  

Sejam reversíveis!
  
[https://www.tecconcursos.com.br/questoes/319979](https://www.tecconcursos.com.br/questoes/319979)

**Cifras de Substituição**
As cifras de substituição podem ser: 

 **Monoalfabética** (substituição simples): deslocamento feito letra por letra. 

Ex: cifra de César.  

**Polialfabéticas**:  Constituída de várias cifras de César em sequência com uma palavra-chave (de mesmo tamanho do texto), utilizada para cifrar e decifrar. 

Ex: cifra de Vigenère

  

![[Pasted image 20240729061840.png]]

  

**Princípio de Kerckhoffs**  


Os algoritmos devem ser públicos e as chaves mantidas em segredo
  
```ad-question
(CESPE 2012 LIQUIGÁS ) Os sistemas criptográficos contemporâneos se valem do poder de processamento dos computadores para criar algoritmos difíceis de quebrar. Essa mesma capacidade de processamento é uma das forças da criptoanálise. Nesse contexto, um dos conceitos (princípio de Kerckhoffs) que prevalecem para certificar ou homologar algoritmos criptográficos é que eles devem ser tão bem construídos que sua resistência a ataques de criptoanálise não deve residir no sigilo do algoritmo, mas, unicamente, no segredo da(o): 

a) chave

b) identidade do remetente 

c) assinatura do remetente 

d) identidade do destinatário e) canal de transmissão

Gabarito: A

```

[https://www.tecconcursos.com.br/questoes/231114](https://www.tecconcursos.com.br/questoes/231114)

[https://www.tecconcursos.com.br/questoes/1422081](https://www.tecconcursos.com.br/questoes/1422081)

[https://www.tecconcursos.com.br/questoes/318241](https://www.tecconcursos.com.br/questoes/318241)

**CRIPTOGRAFIA SIMÉTRICA E ASSIMÉTRICA**

  
![[Pasted image 20240729062355.png]]

Quanto ao número de chaves

* Simétricos 1 chave  x  Assimétricos 2 chaves

**Bloco:** conjunto de blocos de textos agrupados. 

**Fluxo:** fluxo contínuo de arquivos de dados. 

**Criptografia de Chave Simétrica**

 • Criptografia convencional, de chave secreta, de chave privada, de chave compartilhada, e de chave única.

 • Mesma chave para cifrar e decifrar.

  

![[Pasted image 20240729062554.png]]

  

Esquema de Criptografia Simétrica São 5 componentes

• Texto claro; 
• Algoritmo de criptografia;
• Chave secreta;
• Texto cifrado; 
• Algoritmo de decriptografia. 

  [https://www.tecconcursos.com.br/questoes/212197](https://www.tecconcursos.com.br/questoes/212197)

**Esquema de Criptografia Simétrica** 

– Usam as técnicas de substituição e transposição.
– Podem ser por caracteres ou bits. 
– Possibilidade de “quebra” é através do ataque de “Força Bruta”.
– Dependerá do tamanho da chave e do poder computacional. 
– Vantagem: são mais rápidos que os assimétricos. 
– Problema: Compartilhamento da chave.

[https://www.tecconcursos.com.br/questoes/374128](https://www.tecconcursos.com.br/questoes/374128)

  

**Algoritmos de Chave Simétrica**

**Bloco** 
Faz o processamento de bloco em bloco.
•  AES 
• Twofish 
• Serpent 
• Blowfish 
• DES
• 3DES 
• IDEA
• RC5

**Fluxo**

 – One Time Pad (OTP) → uma vez utilizada a chave ela logo é descartada.
 – RC4

[https://www.tecconcursos.com.br/questoes/211778](https://www.tecconcursos.com.br/questoes/211778)

**CRIPTOGRAFIA CIFRA DE BLOCO E DE FLUXO**

**Modo de Processamento – Cifra de Bloco** 
• Cada bloco de tamanho fixo é cifrado por vez.
• Um conjunto de operações matemáticas envolvendo a chave é repetido a cada bloco.
• Não é possível criptografar menos que um tamanho de bloco determinado pelo algoritmo de cifra. 
• Caso o bloco seja menor, será utilizada a técnica de padding. 
• Efetuam-se operações de substituição e transposição simultaneamente. 
• Os métodos de cifras de bloco são: 
 – Eletronic Code Book (ECB) 
 – Cipher Block Chaining (CBC) 
 – Cipher Feedback Block (CFC) 
 – Output Feedback Block (OFB) 
 – Counter (CTR)

**Eletronic Code Book (ECB)**
 • O modo divide a mensagem em blocos de tamanho fixo determinado pelo algoritmo. 
Ex.: DES – blocos de 64 bits. 
• Cada bloco é cifrado e depois são concatenados em ordem.
• Blocos de mensagem idênticos resultarão em blocos cifrados idênticos. 
• Desvantagem: possibilidade de descoberta do texto por criptoanalista! 
• Vantagem: erro em um bit danificar somente aquele bloco, devido à independência entre eles. 

  

![[Pasted image 20240729062835.png]]

[https://www.tecconcursos.com.br/questoes/368507](https://www.tecconcursos.com.br/questoes/368507)

  
**Cipher Block Chaining (CBC)**
 • Para contornar a deficiência do modo EBC.
 • Nesse modo, é realizada uma operação XOR entre o bloco de texto plano e o vetor de inicialização (IV), a mesma chave é usada para cada bloco.
 • Permite que um mesmo bloco de texto claro, quando repetido, produza blocos cifrados diferentes. 
• Um erro de bit em um bloco compromete todos os outros blocos.

  

![[Pasted image 20240729062905.png]]

![[Pasted image 20240729062943.png]]

[https://www.tecconcursos.com.br/questoes/339500](https://www.tecconcursos.com.br/questoes/339500)

**Cipher Feedback Block (CFB)**
• Permite qualquer tamanho de entrada, independentemente do bloco. 
• O bloco cifrado é utilizado para embaralhar os blocos seguintes. 
• Os blocos devem chegar em sequência, senão haverá problema no momento de decifrar. 
• Desempenho menor do modo ECB

  ![[Pasted image 20240729063010.png]]

![[Pasted image 20240729063025.png]]

**Output Feedback Block (OFB)**
• Modo similar ao CFB.
• A exceção é que o resultado da cifra obtida entre o IV e a chave é aplicada ao próximo bloco. 
• Antes de realizar o XOR com o texto claro.

**Counter (CTR)** 
• Modo que veio para resolver o problema dos modos CBC e CFB.
• A impossibilidade de conseguir acesso aleatório em dados codificados. 
Ex.: acesso a arquivos de disco que são acessados de modo não sequencial, como arquivos de banco de dados. 

**Cifra de Fluxo**
 • Operam criptografando a mensagem na medida em que os dados vão chegando. 
• As cifras podem ocorrer bit a bit, byte a byte e até em intervalos específicos de tempo.
 • A sequência de bits gerados será usada como chave, keystream, composta pela chave inicial e o IV. 
• A cifra se dá pela combinação: texto claro + keystream e operação de XOR

[https://www.tecconcursos.com.br/questoes/342027](https://www.tecconcursos.com.br/questoes/342027)
[https://www.tecconcursos.com.br/questoes/319980](https://www.tecconcursos.com.br/questoes/319980)

**CRIPTOGRAFIA – ALGORITMOS DE CRIPTOGRAFIA SIMÉTRICA**

**Algoritmos Simétricos**

| Bloco    | Fluxo              |
| -------- | ------------------ |
| AES      | On Time Pad ( OTP) |
| Twofish  | RC4                |
| Serpent  |                    |
| Blowfish |                    |
| DES      |                    |
| 3DES     |                    |
| IDEA     |                    |
| RC5      |                    |

**DES – Data Encryption Standard** 
• Criado pela IBM em 1977. 
• Utiliza chaves de 64 bits, sendo 56 bits randômicos e 8 bits de paridade.
• Força efetiva da chave é de 56 bits. 
• Seu tamanho de chave é pequena em relação aos demais algoritmos. 
• Tamanho fixo em blocos de 64 bits. 
• Foi quebrado em 1997 em um desafio lançado pelo NIST.
• Pode utilizar qualquer dos modos de cifração.
• Utiliza 16 rodadas com técnicas de permutação e substituição.
• Utiliza também o conceito de S-Boxes nos processos de substituição de bits. 
• Havia acusações de inserção de Backdoors nessas S-Boxes pela NSA.
• A essa forma de organização é conhecida como cifra de Feistel. 

**3DES – Triple Data Encryption Standard** 

• Surgiu para dar sobrevida ao DES.
• Constitui-se na aplicação do DES por três vezes. 
• Apesar de totalizar 168 bits de chave, o 3DES suporta a utilização de apenas duas chaves, assumindo que a primeira e a terceira sejam iguais. 
• Sua chave se restringe a 112 bits de força efetiva.

  
![[Pasted image 20240729063048.png]]

  

**AES – Advanced Encryption Standard** 

• Substituto ao DES e padrão do governo americano.
• Chave de 128, 192 e 256 bits. 
• Bloco de 128 bits por padrão. 
• Trabalha com três estágios de substituição (Subbytes, MixColmns e AddRoundKey) e um de permutação (shiftRows).

[https://www.tecconcursos.com.br/questoes/368503](https://www.tecconcursos.com.br/questoes/368503)
[https://www.tecconcursos.com.br/questoes/338285](https://www.tecconcursos.com.br/questoes/338285)
[https://www.tecconcursos.com.br/questoes/295490](https://www.tecconcursos.com.br/questoes/295490)
[https://www.tecconcursos.com.br/questoes/1297237](https://www.tecconcursos.com.br/questoes/1297237)
[https://www.tecconcursos.com.br/questoes/389860](https://www.tecconcursos.com.br/questoes/389860)

**CRIPTOGRAFIA ASSIMÉTRICA**

Criptografia Assimétrica ou criptografia de chave pública.
Chave usada para cifrar é diferente da usada para decifrar

  
```ad-attention

Se houver a necessidade de criptografar algum documento para garantir sua confidencialidade, utiliza-se a chave pública de quem recebe o documento, e quem recebe utiliza a chave privada. 
```


Uma chave é de conhecimento somente do dono (privada) e a outra de conhecimento público (pública).


![[Pasted image 20240729063142.png]]

As chaves são matematicamente relacionadas
Há um alto custo computacional (relação à simétrica). 
Não é possível determinar uma chave privada a partir da sua chave pública correspondente. 
São dois processos possíveis: 
• Confidencialidade 
• Autenticidade e Integridade

```ad-attention

Autenticidade e integridade referem-se à assinatura digital.
```


**Confidencialidade** 

Utiliza-se a chave pública (receptor) para cifrar e a chave privada para decifrar (receptor)

**Autenticidade (autoria)**
Utiliza-se a chave privada (emissor) para criptografar e a chave pública (receptor) para decifrar.

![[Pasted image 20240729063249.png]]

  
  

**Algoritmos de Criptografia Assimétrica**
• Diffie Hellman • El Gamal 
• RSA – Rivest, Shamir and Aldeman 
• ECC – Curvas Elípticas

https://www.tecconcursos.com.br/questoes/785592

**Diffie Hellman** 

• É um protocolo para troca de chaves quando utiliza-se um meio inseguro 
(Ex.: Internet).
• Não é usado para criptografia, mas somente para prover um meio seguro para a troca de chaves, criação de chave de sessão. 
• Seu uso em conjunto com algoritmos de curvas elípticas cria um processo chamado Perfect Forward Secrecy (PFS). 
• A finalidade do PFS é proporcionar resistência aos ataques de sequestro de sessão no HTTPS.
  
**El Gamal** 
• Processo similar ao Diffie Hellman. 
• Sua aplicação é na transferência de assinaturas digitais e trocas de chaves no estabelecimento de comunicações. 
• Possui três componentes básicos: geradores de chaves, algoritmo de cifragem e algoritmo de decifragem. 
• Baseia-se no problema do logaritmo discreto

**RSA – Rivest, Shamir and Aldeman**

• Sinônimo de chave pública. 
• Baseia-se na dificuldade de se fatorar <u>números primos</u> muito grandes. 
• Os tamanhos de chave sugeridos são de 2048 a 4096 bits
• Usualmente, aplicações utilizam chaves de 1024 bits. 
• Quanto maior a chave → maior a segurança → maior o processamento → menor velocidade. 
• Realiza o envelopamento digital, processo de envio das chaves simétricas de forma segura. 

https://www.tecconcursos.com.br/questoes/1423960
https://www.tecconcursos.com.br/questoes/1045



776

**Criptografia de Curva Elíptica – ECC** 
• Elliptic Curve Cryptography – ECC.
 • O aumento do tamanho das chaves RSA nos últimos anos acarretou também aumento no processamento das aplicações usando o RSA (e-commerce). 
• O ECC oferece igual segurança com tamanho de chave muito menor. 
• Chave de 160 bits ECC = chave de 1024 bits RSA

```ad-attention

A carga de processamento e a velocidade ao utilizar uma chave de 160 bits terá uma um processamento menor e velocidade maior em relação a uma chave de 1024 bits usada pelo RSA.
```


[https://www.tecconcursos.com.br/questoes/338888](https://www.tecconcursos.com.br/questoes/338888)
[https://www.tecconcursos.com.br/questoes/215662](https://www.tecconcursos.com.br/questoes/215662)
  
  

**Função de Hash – Integridade e Autenticidade**

• Também conhecida como código de hash, síntese, resumo ou digest de mensagem. 
• Entradas de tamanhos variáveis geram um resultado de tamanho fixo
• Não utiliza chave. 
• Integridade, a mudança em qualquer bit na mensagem resultará na mudança do código de hash (analogia: lacre de uma encomenda)
 
**Função de Hash** 
• É unidirecional.
 • Confidencialidade, não há algoritmos para descobrir a mensagem original a partir do resultado gerado. 

  
![[Pasted image 20240729063345.png]]

  
• Autenticidade, a função de hash é usada para comparar os valores gerados durante o login com os valores armazenados na base de dados desse login. 
• É utilizado em várias aplicações como a assinatura digital

  **Colisão** 

• Quando dois dados originais geram o mesmo resumo, temos uma colisão. 
• Procura-se reduzir ao máximo a probabilidade de ocorrência de colisões em algoritmos de hash

  
**Algoritmos de Hash** 

**MD 5** 

• MD 5 (Message-Digest algorithm 5)
• Saídas de 128 bits.
• Desenvolvido pela RSA Data Security.
• Família MD (MD2, MD3, MD4)

https://www.tecconcursos.com.br/questoes/1423961

**SHA**
• Secure Hash Standard (SHA). 
• Desenvolvido pelo NIST dos EUA. SHA-512 
• Aceita como entrada mensagem com tamanho de 2128 bits. 
• A entrada é processada blocos de 1024 bits.
• A saída será um hash de 512 bits

  

[https://www.tecconcursos.com.br/questoes/323668](https://www.tecconcursos.com.br/questoes/323668)
[https://www.tecconcursos.com.br/questoes/1546577](https://www.tecconcursos.com.br/questoes/1546577)
[https://www.tecconcursos.com.br/questoes/369550](https://www.tecconcursos.com.br/questoes/369550)
[https://www.tecconcursos.com.br/questoes/316475](https://www.tecconcursos.com.br/questoes/316475)
[https://www.tecconcursos.com.br/questoes/368508](https://www.tecconcursos.com.br/questoes/368508)
 
  

**Caderno com as questões**

[https://www.tecconcursos.com.br/s/Q25kwA](https://www.tecconcursos.com.br/s/Q25kwA)



#flashcards 

o que é Esteganografia;;É o estudo e uso das técnicas para ocultar a existência de uma mensagem dentro de outra.
<!--SR:!2024-09-19,3,250-->