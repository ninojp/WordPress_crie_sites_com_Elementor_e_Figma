# Curso Alura - WordPress: crie sites com Elementor e Figma

Estou fazendo este curso apenas para relembrar e me atualizar sobre o Word Press, pois já fiz três curso sobre este assunto no canal do Curso em video(prof. Guanabara).  
O segundo motivo é que peguei dois sites para fazer, e por diversos motivos implementalos em WP será muito mais interessante. Por isso não terá o projeto das aulas aqui no repositório, terá apenas o conteúdo escrito(resumo Aluri).

## Aula 01 - Visão geral

### Aula 01 - Apresentação - Video 1

Nesta aula do curso de WordPress com Elementor e Figma, o instrutor Jhonatan Jacinto, também conhecido como Jota, apresenta uma visão geral do curso. Ele explica que o objetivo é introduzir os alunos à plataforma WordPress, com foco no uso do plugin Elementor. Durante o curso, os alunos aprenderão a utilizar o WordPress e suas ferramentas, como plugins, temas e ferramentas de edição visual. Também será apresentado o uso da ferramenta de design Figma para explorar os elementos visuais antes de transferi-los para a estrutura do site. Não é necessário conhecimento prévio em programação, mas ter noções básicas de HTML pode ser útil. O curso é prático e visual, permitindo que os alunos construam seus primeiros sites mesmo sem conhecimento aprofundado em programação. Ao final do curso, os alunos estarão aptos a criar sites administráveis e customizáveis, atendendo às necessidades dos clientes.

### Aula 01 - Ferramentas necessárias - Video 2

Nesta aula, o instrutor discute as ferramentas necessárias para a construção de um site usando o Elementor e o Figma. São mencionadas duas ferramentas principais: o XAMPP e o WordPress. O XAMPP é um conjunto de ferramentas que cria um ambiente de execução do site, incluindo o servidor Apache, o banco de dados MariaDB, e as linguagens de programação PHP e Perl. O WordPress é a ferramenta utilizada para a construção das páginas, posts e demais elementos do site. O instrutor destaca a importância de baixar as versões mais recentes dessas ferramentas para garantir segurança e correção de bugs. Com o XAMPP e o WordPress baixados, já é possível iniciar a criação do site.

### Aula 01 - Instalando o XAMPP - Video 3

Nesta aula, o instrutor explica o processo de instalação do XAMPP, um ambiente de execução utilizado para desenvolvimento web. Ele mostra como fazer o download, abrir a pasta de instalação e executar o instalador. Durante a instalação, são exibidas janelas de configuração onde é possível selecionar os componentes a serem instalados, a pasta de instalação e o idioma. Após a conclusão da instalação, o instrutor destaca a importância dos módulos Apache e MySQL e mostra como iniciar esses serviços no Painel de Controle do XAMPP. Ele também ensina como verificar se os serviços estão funcionando corretamente através das páginas do Apache e do phpMyAdmin. No final, o instrutor menciona que falta apenas instalar o WordPress.

### Aula 01 - Instalando o WordPress - Video 4

Nesta aula, o instrutor aborda a instalação e configuração do WordPress utilizando o XAMPP. Ele explica como extrair os arquivos do WordPress, criar um banco de dados exclusivo para o projeto e copiar a pasta do WordPress para o diretório de instalação do XAMPP. Em seguida, ele mostra como acessar o WordPress no navegador e preencher o formulário de instalação com os dados do banco de dados. Após preencher o formulário, o instrutor destaca a importância de clicar no botão "Criar" para gerar o banco de dados. Ele também explica como criar a página do WordPress e destaca a importância de clicar no botão "Instalar WordPress" para concluir a criação do banco de dados. Por fim, o instrutor mostra como acessar o painel administrativo do WordPress e como visitar o site público.

### Aula 01 - Para saber mais: a importância do prefixo wp_

O prefixo padrão da tabela é uma informação pública e conhecida por muitos hackers, o que pode facilitar ataques ao seu site. Mudar o prefixo da tabela pode tornar mais difícil para os invasores adivinharem o nome das tabelas em seu banco de dados.  
Mudar o prefixo da tabela é um processo relativamente simples, contudo requer certo conhecimento técnico pois envolve não apenas editar o arquivo wp-config.php na raiz do seu site alterando a linha table_prefix (que faz referência ao prefixo utilizado atualmente pelas tabelas de dados da aplicação) como também acessar o banco de dados para efetivação da alteração dos prefixos e, finalmente, atualizar todas as referências aos nomes antigos das tabelas do banco para os novos nomes, o que exige conhecimentos da linguagem SQL de manipulação de banco de dados. Sendo assim, o melhor momento para definir e escolher um prefixo para as tabelas do banco de dados do seu site é o momento da instalação do WordPress mesmo.

### Aula 01 - Ao longo dessa primeira aula conhecemos

WordPress:  
As principais características, porque escolhemos esta solução para o desenvolvimento do projeto e como realizar seu download e instalação e;
XAMPP:  
Uma ferramenta necessária para instalação e configuração de um ambiente propício à execução de aplicações WordPress (e outros tipos também) diretamente em nossa máquina, “emulando” um cenário próximo ao de produção.

## Aula 02 - Configurando o WordPress

### Aula 02 - Estrutura de conteúdo - Video 1

Nesta aula, o instrutor discute a importância do uso do Figma, uma ferramenta de design de interface, para criar o layout do site da Jornada Viagens. Ele explica como criar uma conta gratuita no Figma e como essa conta será útil para acompanhar o curso e analisar o layout compartilhado. Além disso, o instrutor destaca que o Figma fornece acesso às características estéticas do site, como cores e tamanhos de fonte, que serão necessárias para transpor o layout para o WordPress. Ele sugere que o próximo passo é analisar o layout do site e descobrir como traduzir esse conteúdo para dentro do WordPress, que possui uma estrutura pronta e classifica os conteúdos em temas, posts, categorias, tags e páginas. O instrutor menciona que irá abordar cada uma dessas categorias ao longo do curso, começando pelo tema, que é a parte fundamental de qualquer site WordPress.

