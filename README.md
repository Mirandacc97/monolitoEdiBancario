# monolitoEdiBancario

Depois de pensar um pouco sobre o que seria mais útil e interessante para o trabalho final, decidi criar o “Monolito Integrador Bancário”. 
A ideia é montar um site que sirva como uma espécie de painel central para empresas cadastrarem seus dados bancários, pagamentos, cobranças e fazerem a conciliação de extratos. 
Quero que a interface seja bem neutra, tipo white label, para facilitar adaptações no futuro e deixar o sistema com cara de produto pronto para ser integrado a outros serviços, como um SaaS de EDI bancário.

### Estrutura das Páginas

Estou planejando dividir o sistema em quatro partes principais:
- **Home:** Aqui vou mostrar um resumo financeiro das movimentações, para dar uma visão geral da situação financeiro do usuário.
- **Cadastro de empresas, bancos e dados de integração:** Essa parte vai ter formulários para cadastrar empresas, contas e as informações que o banco pede para autenticação.
- **Cadastro de pagamentos e cobranças:** Nessa tela, o usuário vai conseguir registrar pagamentos e cobranças. Quero adicionar uma função para ler o código de barras dos boletos, para agilizar o processo.
- **Conciliação de extrato bancário:** Aqui a ideia é mostrar todos os títulos cadastrados e comparar com as movimentações do extrato, permitindo conciliar o que já foi pago ou recebido.

### Interface e Visual

Pretendo usar um menu fixo para facilitar a navegação entre as páginas. Ainda estou escolhendo as cores, mas provavelmente vou apostar em azul, branco e cinza, que são bem comuns em sistemas bancários e passam uma sensação de confiança. O site só ira funcionar no computador.

### Tecnologias

Vou fazer tudo em HTML5 e CSS3, criando um arquivo de estilos externo para garantir que o visual fique padronizado. 
Se der tempo, pretendo colocar um pouco de JavaScript para validar formulários e talvez ajudar na leitura do código de barras.

### Organização e Documentação

Como estou fazendo o projeto sozinho, vou documentar tudo no README do repositório do Github, explicando o que cada parte faz e como usar.

### Cronograma

Já defini o escopo e criei o repositório. Agora vou focar em montar as páginas e implementar as funcionalidades até a data da entrega.