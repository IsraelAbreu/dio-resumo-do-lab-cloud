# Modulo 1 - Conceitos de Nuvem
Este repositório contém o resumo das lições aprendidas durante o desenvolvimento do lab na DIO da formação AZ-900

## Resumo sobre o lab 1: Localizando serviços por Categoria e Personalização.
Durante o primeiro lab consegui aprender sobre a personalização da minha plataforma Azure, como: Exibição do Menual Lateral e Mudanças na aparência da plataforma. No segundo momento do Lab aprendemos a acessar a guia de + Criar Recurso e navegar no menu de  "Todos os serviços", no qual é exibidos todos os serviços que a plataforma disponibiliza. A professora tambéma abordou um ponto importante sobre os serviço que estão como  "Prévia" no qual esses serviços não possuem uma garantia de que vão continuar disponiveis na plataforma, por isso devemos ter cuidado ao usar esse tipo de serviços para um ambiente de produção.

## Resumo sobre o lab 2: Criando máquinas Virtuais na Azure.

Durante esse Lab, o assunto abordado foi sobre SLA que estão diretamente ligados ao tempo de indiponibilidade de um serviço ou recurso da nuvem. 
É importante lembrar que alguns serviço já possuem um SLA padrão definido e outros recursos como Máquinas Virtuais esse tempo de disponibilidade pode ser configurado.
Uma configuração que tamém pode ser adiconada ao criar uma máquina virtual é as "opções de disponibilidade", como a opção de zona de disponibilidade onde o recuso é separado fisicamente em uma região mantém assim o recursos sempre disponível e de facil acesso para o caso de algum desastre.

## Resumo sobre o lab 3: Configurando uma instância de Banco de Dados na Azure.

Nesse último Lab do módulo 1, aprendemos a criar uma instância de um banco de dados no Azure. Um ponto importante é que já que estamos um SaaS, não criamos um servidor próprio para nossa instância do nosso banco de dados, durante a criação da nossa instância de banco é importante definir um nome simbólico para o servidor onde o serviço vai ser hospedado, não vamo ter acesso a esse servidor já que a Azure vai criar esse servido por baixo dos panos para nosso serviço ser executado.

Também definimos configurações de segurança para autênticação, escolhendo entre as opções abaixo:
 - Windows AutenticaID
 - Windows AutenticaID + MySQL
 - Apenas MySQL.

Ao final das configurações a calculadora do Azure vai exibir o valor do nosso serviço.

# Módulo 2 - Arquitetura do Azure

## Resumo sobre o lab 1: Componentes de Arquiteturas do Azure

Durante esse módulo foi aprendido sobre os sites fornecidos pela Microsoft para mais informação sobre datacenters e regiões ao redor do mundo.
O foco do aprendizado desse módulo foi a criação de um grupo de recurso por meio do Portal da Azure. Ao criar e acessar um grupo de recursos temos como verificar logs de atividades, visualizador de recursos que é uma funcionalidade bem massa, onde os recursos criados dentro do grupo são estruturados em forma de uma árvore, podemos também criar eventos automatizados, verificar as etapas dos serviços criados em Inplantações e gerenciar politicas de seguraná em 'Segurança'. 
