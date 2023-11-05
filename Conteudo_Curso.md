# Curso Alura - WordPress: crie sites com Elementor e Figma

Estou fazendo este curso apenas para relembrar e me atualizar sobre o WordPress, pois já fiz três curso sobre este assunto no canal do Curso em video(prof. Guanabara).  
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

### Aula 02 - Para saber mais: Figma

Já imaginou uma mesa de desenho digital, onde várias pessoas podem colaborar em um projeto em tempo real, desenhando e ajustando seus esboços juntos? Então, esta ferramenta existe!

O Figma é uma ferramenta de design colaborativo baseada em nuvem. Sua utilização é especialmente útil para pessoas que desejam criar interfaces de usuário (UI) destinadas não apenas a websites como também aplicativos mobile ou mesmo aplicações para desktop.

Assim como uma mesa de desenho, o Figma oferece uma ampla variedade de ferramentas e recursos para ajudar a criar designs precisos e profissionais. A diferença é que o Figma é baseado em nuvem, o que significa que as pessoas podem colaborar de qualquer lugar do mundo, tornando o processo de design ainda mais ágil e flexível além da ferramenta em si poder ser executada diretamente em seu navegador web.

### Aula 02 - Temas - Video 2

Nesta aula, o instrutor discute sobre temas no WordPress. Um tema é um conjunto de arquivos que define a aparência e o comportamento de um site WordPress. É possível personalizar o tema utilizando plugins ou recursos de customização próprios do tema. Na área administrativa do WordPress, é possível acessar a seção "Aparência" e, em seguida, "Temas" para visualizar e ativar diferentes temas. Além dos temas pré-instalados, é possível adicionar novos temas ao WordPress, tanto gratuitos quanto específicos. Gerenciar temas no WordPress envolve escolher, instalar, ativar e personalizar temas de acordo com as necessidades e preferências do usuário.

### Aula 02 - Posts, categorias e tags - Video 3

Nesta aula, o instrutor discute sobre os posts, categorias e tags no WordPress. Os posts são a forma básica de classificar conteúdo, representando publicações com data de publicação e autor associados. As categorias são usadas para organizar e agrupar posts relacionados a um mesmo tema, enquanto as tags são mais específicas e abordam um tópico claro. As categorias têm uma natureza hierárquica, permitindo a criação de uma hierarquia de categorias, enquanto as tags são mais flexíveis. No próximo vídeo, o instrutor ensinará como aplicar na prática o uso de posts, categorias e tags no WordPress.

### Aula 02 - Conclusão, Nessa aula aprendemos

Sobre o Figma e como ele funciona;
O que é e para que serve os temas no WordPress;
Entendemos a diferença entre posts, categorias e tags.

## Aula 03 - Apresentando o Elementor

### Aula 02 - Gerenciando posts, categorias e tags - Video 1

Nesta aula do curso "WordPress: crie sites com Elementor e Figma", o instrutor Jhonatan Jacinto aborda a área administrativa do WordPress, focando na seção de "Posts". Ele explica como visualizar a lista de posts cadastrados, a importância de categorizar os posts e como cadastrar categorias no WordPress. Além disso, o instrutor também fala sobre o uso de tags para agrupar conteúdos e como associar categorias e tags a um post específico. Ele mostra como adicionar um novo post, destacando a importância da data de publicação na ordenação dos posts. Por fim, o instrutor menciona a exibição dos posts na página inicial do site e como visualizar os posts relacionados a uma tag específica. Na próxima aula, serão abordadas as diferenças entre páginas e posts no WordPress.

### Aula 02 - Páginas - Video 2

Nesta aula, foi apresentado o conceito de páginas no WordPress e como elas se diferenciam de posts. As páginas são conteúdos estáticos, com atualizações menos frequentes, e não possuem categorização ou tags. Para trabalhar com páginas, é necessário acessar a área administrativa e selecionar a opção "Páginas". É possível definir uma página como a página inicial do site e criar uma estrutura hierárquica de páginas. O processo de criação de páginas é mais simples do que o de posts. O próximo passo é aplicar o layout definido pelo designer.

### Aula 02 - Instalando e customizando o tema - Video 3

Nesta aula, o instrutor apresenta o Elementor como uma ferramenta para implementar os aspectos visuais de um site no WordPress. Ele explica que o design é feito no Figma e que serão utilizadas duas ferramentas para transferir essas características para o WordPress: a ferramenta de personalização dos temas do WordPress e o plugin Elementor. O instrutor mostra como instalar o tema "Astra" e personalizar o cabeçalho do site, alterando a cor de fundo e substituindo o texto pelo logo da empresa. Ele também explica como configurar o menu do site de acordo com o layout do Figma, adicionando páginas e links personalizados. As customizações visuais do menu serão abordadas no próximo vídeo.

### Aula 02 - Finalizando o menu - Video 4

Nesta aula, o instrutor discute sobre a configuração estética do menu em um site utilizando o WordPress. Ele mostra como acessar a aba "Design" do menu e alterar a cor dos itens e links, além de definir a fonte específica do menu. O instrutor também menciona que a configuração do ícone de bandeira para selecionar o idioma será abordada posteriormente. Por fim, ele explica como salvar as alterações e voltar para a área administrativa.

### Aula 02 - Conclusão Nessa aula aprendemos

A gerenciar posts, categorias e tags;
A criar páginas e vimos como configurá-las;
Instalar e personalizar um tema;
A deixar o menu de navegação com uma boa experiência de usuário.

## Aula 03 - Sessões da Hpme

### Aula 03 - Explorando o Elementor e construindo o banner - Video 1

Nesta aula, o instrutor ensina como ajustar a fonte do menu e criar uma seção de banner utilizando o Elementor no WordPress. Ele explica passo a passo como acessar os elementos do layout, fazer as modificações desejadas e salvar as configurações. O Elementor oferece mais liberdade de edição do que os recursos do tema, permitindo ajustes mais simples no topo e rodapé do site. O instrutor também mostra como configurar a largura do conteúdo, ocultar o título da página e definir uma imagem de fundo para a seção de banner. No final, ele menciona que o banner está configurado e que podem prosseguir para a próxima parte do vídeo.

### Aula 03 - Seção boas-vindas - Video 2

Nesta aula, o instrutor ensina como configurar a seção de boas-vindas em um site utilizando o Elementor. Ele mostra como criar uma nova seção, definir o título, configurar a cor e a fonte do texto, adicionar um divisor e um texto abaixo dele. Também é explicado como ajustar o espaçamento entre os elementos. O instrutor finaliza mencionando que a configuração da seção de boas-vindas está concluída e que no próximo vídeo será ensinado como replicar essa seção no Elementor.

Ofertas da semana