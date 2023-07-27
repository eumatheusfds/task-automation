# Automatização de Tarefas com Python

Neste projeto, imagine que você precisa cadastrar centenas de produtos, preços ou outras informações em um sistema, e fazer tudo isso manualmente seria um trabalho árduo e demorado.
Utilizando Python, vamos aprender a controlar o mouse e o teclado para executar tarefas repetitivas de forma automática. 

A ideia é: vamos criar um script capaz de entrar em um site (especialmente criado para este projeto), fazer login e cadastrar todos os produtos de maneira automática. Imagine o tempo que economizaremos e o potencial para aumentar a eficiência de nossos processos!

Os dados que nós vamos utilizar são as informações que estão dentro do arquivo produtos.csv. Nesse arquivo temos diversos produtos para serem cadastrados no sistema de forma automática.

Temos o código do produto, marca, tipo, preço unitário, custo e observação. Só que o primeiro ponto, é que as informações estão no formato csv, o que dificulta um pouco a visualização. Outro ponto é que temos 264 linhas de informação, então você teria que preencher 6 informações no sistema para cada linha da base de dados. É para evitar esse tipo de trabalho manual que vamos criar automações com Python. Com isso o trabalho fica muito mais rápido, automático e sem chances de inserir informações erradas.

A solução desse projeto vai ser exatamente a nossa automação, ou seja, vamos ter no final todos os produtos da nossa base de dados cadastrados no sistema de forma automática, como se você estivesse utilizando o computador para fazer o cadastro. Ao rodar o programa vamos ter as seguintes ações para completar o nosso cadastro:

    • Abrir o navegador
    • Acessar o site do sistema com login e senha
    • Inserir todas as informações do produto
    • Enviar as informações para o sistema
    • Repetir o cadastro até acabar o cadastro de todos os produtos
