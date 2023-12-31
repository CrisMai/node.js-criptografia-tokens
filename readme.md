
Uma breve história da criptografia

Palavra originada do grego e significa algo como “escrita oculta”. 
A técnica consiste basicamente em ocultar mensagens através de códigos.
Embora a criptografia moderna e sua aplicação na tecnologia da informação 
por meio de computadores seja algo novo, a prática de ocultar informações 
através de códigos vem de longa data, de cerca de 4.000 anos.

Desde então, possuímos inúmeras técnicas para criptografar informações. 
De forma geral, há duas formas de ocultar uma mensagem, através de códigos 
ou através das chamadas cifras.

As técnicas de cifragem podem ser agrupadas em:

Cifras de Transposição: método que consiste na ordenação diferente de letras 
de uma mesma mensagem. Por exemplo, podemos cifrar o nome “CAMILA” por “ALIAMC”.

Cifras de Substituição: esse método criptográfico opera, como o próprio nome sugere, 
a partir da substituição de letras, pares ou grupos de letras em um sistema pré-estabelecido. 
Em outras palavras, nas cifras de substituição, a mensagem continua na mesma ordem mas 
as unidades de textos são alteradas. 


Funções de Hash

Funções de hash é como uma cifra, mas que apenas mistura a informação, não sendo um 
processo reversível.
Existem vários tipos de função de hash, como MD5, SHA1 e SHA-256.


Encriptação

A encriptação, também conhecida como criptografia, é um processo de transformação de 
dados legíveis em um formato ilegível, chamado de texto cifrado ou criptograma. 
Esse processo é usado para proteger a confidencialidade e a segurança das informações, 
tornando-as ininteligíveis para qualquer pessoa não autorizada que possa interceptá-las.


Encriptação Simétrica

É um tipo de criptografia em que a mesma chave é usada tanto para encriptar quanto 
para descriptografar os dados. Isso significa que o remetente e o destinatário da 
mensagem precisam compartilhar a mesma chave secreta para garantir a comunicação 
segura.


Encriptação Assimétrica

A encriptação assimétrica é um método de criptografia que utiliza um par de chaves 
diferentes: uma chave pública para encriptação e uma chave privada para descriptografia. 
Ela oferece recursos adicionais de segurança e autenticação em comparação com a 
encriptação simétrica, tornando-se uma escolha comum em muitos cenários de 
segurança de dados.


Assinatura Digital

Uma assinatura digital é um mecanismo criptográfico utilizado para verificar a 
autenticidade, a integridade e a autoria de um documento ou mensagem eletrônica. 
Ela fornece uma forma de garantir que o conteúdo de um documento não tenha sido 
alterado após ter sido assinado e também permite verificar se o documento foi 
realmente assinado pela pessoa ou entidade declarada como signatária.

A assinatura digital utiliza técnicas de criptografia assimétrica, que envolvem 
o uso de um par de chaves: uma chave privada e uma chave pública. A chave privada 
é mantida em sigilo pelo proprietário e é usada para criar a assinatura digital, 
enquanto a chave pública é divulgada publicamente e usada para verificar 
a assinatura.


Sessões e Tokens

Sessão: Quantidade de tempo em que o usuário está autenticado e conectado a um 
serviço ou um sistema.

Token: Solução para gerar como se fosse uma hash de uma determinada informação 
e enviado de volta para o usuário. O usuário apenas aguarda essa hash, não consegue 
ler e não possui capacidade de utilizar. Quando o usuário for fazer uma requisição, 
ele vai mandar esse token de volta e ao invés do servidor pesquisar e localizar esse ID, 
ele simplesmente valida o token, ou seja, vai decifrar a informação.


Algoritmos Criptográficos

Algoritmos criptográficos são procedimentos matemáticos e lógicos que são usados 
para cifrar e decifrar dados. Os algoritmos criptográficos desempenham um papel 
fundamental na proteção da confidencialidade, integridade e autenticidade das 
informações em sistemas de comunicação e armazenamento de dados. 
Eles são amplamente utilizados em diversas aplicações, como segurança de redes, 
criptografia de dados em trânsito (como HTTPS) e em sistemas de autenticação 
e assinatura digital.


Ataques Criptográficos

Ataques criptográficos são tentativas de comprometer a segurança de um sistema 
criptográfico com o objetivo de obter informações protegidas ou explorar 
vulnerabilidades no algoritmo criptográfico usado.
Existem diferentes tipos de ataques criptográficos, cada um com suas próprias 
características e objetivos. Alguns exemplos comuns são:
-Ataques de força bruta;
-Ataque de dicionário;
-Ataque rainbow table.