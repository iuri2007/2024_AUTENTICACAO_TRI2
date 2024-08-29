# 2024_AUTENTICACAO_TRI2

# 1. Autenticação de Usuários (Servidor Único)

## O que é? 

- Imagine que você vai entrar em uma festa exclusiva. Na entrada, há um segurança que verifica se seu nome está na lista. Se o seu nome estiver na lista, ele deixa você entrar. Autenticação é exatamente isso: é o processo de verificar se você é quem diz ser. No mundo dos computadores, é como provar sua identidade para um sistema.

- Servidor Único significa que todos os processos de verificação acontecem em um único lugar, como se houvesse apenas uma entrada na festa e todos os convidados precisassem passar por esse mesmo segurança.

## Exemplo: 
- Quando você acessa seu e-mail, você digita seu nome de usuário e senha. O servidor de e-mail (o "segurança") verifica essas informações. Se estiverem corretas, ele deixa você acessar sua caixa de entrada.

# 2. Autenticação VS Autorização

## O que é?

- Esses dois termos podem parecer complicados, mas vamos simplificá-los com um exemplo do mundo real.

## Autenticação: 

- Imagine que você está na porta de um prédio de escritórios. Para entrar, você precisa mostrar sua identificação (um crachá, por exemplo). Isso é autenticação — provar que você é quem diz ser.

## Autorização:

-  Agora que você entrou no prédio, você precisa acessar uma sala específica. Mas só porque você entrou no prédio não significa que você pode entrar em qualquer sala. Talvez você tenha permissão para acessar a sala de reuniões, mas não a sala do diretor. Isso é autorização — decidir aonde você pode ir ou o que você pode fazer depois que já provou quem você é.

## Exemplo:

- Em um site de banco, primeiro você faz login (autenticação). Depois, dependendo do seu tipo de conta, você pode transferir dinheiro ou apenas visualizar o saldo (autorização).

# 3. Autenticação com Token (JWT)

## O que é? 

- Pense no JWT (JSON Web Token) como um ingresso de cinema. Quando você compra o ingresso, ele tem todas as informações necessárias para permitir sua entrada (como o filme, a sala, e a hora). Assim, quando você chega no cinema, basta mostrar o ingresso e você pode entrar sem precisar explicar tudo de novo.

- No mundo da programação, JWT funciona de maneira semelhante. Após você fazer login e ser autenticado, o sistema gera um token (como seu "ingresso") que contém informações sobre você. Este token é enviado de volta para o seu navegador, e toda vez que você faz uma nova solicitação ao servidor (como acessar outra página), você envia esse token. O servidor, então, verifica o token para garantir que você tem permissão para fazer o que está tentando.

## Exemplo: 

- Você faz login em um aplicativo de redes sociais e recebe um JWT. A partir daí, sempre que você faz uma ação no aplicativo, como postar uma foto ou curtir uma postagem, seu JWT é enviado para o servidor para verificar se você está autorizado a fazer isso. Isso evita que você tenha que fazer login novamente a cada ação.

# 4. Projeto (Objeto de Estudos)

## O que é?

- O Projeto (Objeto de Estudos) é simplesmente o tema ou foco do trabalho que você está fazendo. Pense nisso como o objetivo final de uma tarefa ou pesquisa.

## Exemplo: 

- Suponha que você está em uma aula de ciências e seu professor pede para você fazer um projeto sobre a fotossíntese. O projeto seria criar uma apresentação ou relatório explicando como a fotossíntese funciona. Nesse caso, a fotossíntese é o objeto de estudo — ou seja, o tema principal sobre o qual você está aprendendo e apresentando informações.

## Outro exemplo: 

- Se você está aprendendo a programar e seu professor pede para você criar um site simples como projeto, o objeto de estudo seria o próprio processo de criar esse site, aprendendo como escrever código, estruturar páginas, etc.

#### Essas explicações usam exemplos cotidianos para ajudar a visualizar como esses conceitos funcionam na prática, facilitando o entendimento, especialmente se você não está familiarizado com a terminologia técnica.