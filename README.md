# DIO-Azure-AZ-03
Microsoft Azure: Tipos de serviços na nuvem e responsabilidades

Os modelos de serviço na Azure definem o nível de controle, gerenciamento e responsabilidade que os usuários têm sobre os recursos da nuvem. Eles variam desde a infraestrutura completa fornecida como serviço até aplicações completamente gerenciadas. Segue uma descrição dos tipos de serviços:

## IaaS (Infrastructure as a Service)
Fornece aos usuários acesso a recursos de computação, como servidores virtuais, armazenamento e redes, na nuvem. Os usuários têm controle total sobre a infraestrutura, mas não precisam se preocupar com a gestão física dos servidores. Isso permite uma escalabilidade rápida, flexibilidade e a possibilidade de executar qualquer sistema operacional ou aplicação.

Exemplo no Azure: máquinas virtuais do Azure (Azure Virtual Machines) permitem aos usuários implantar uma VM na nuvem, que pode ser configurada para diversos tamanhos e propósitos, desde servidores de jogos até servidores de aplicações complexas.

Responsabilidade da Azure: a Microsoft é responsável pela segurança da infraestrutura física dos data centers, a rede, e a hospedagem de serviços. Isso inclui a proteção contra ameaças à infraestrutura física, como desastres naturais ou ataques físicos.

Responsabilidade do cliente: os clientes são responsáveis pela segurança do sistema operacional, aplicações e dados que operam nas máquinas virtuais. Isso inclui a gestão de controles de acesso, a proteção de suas redes virtuais e a criptografia de seus dados.

Referência: https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-iaas/

## PaaS (Platform as a Service)
Oferece um ambiente de desenvolvimento e implantação na nuvem, onde os usuários podem criar, gerenciar e hospedar aplicações sem se preocupar com a infraestrutura subjacente. Este modelo é ideal para desenvolvedores que querem se concentrar no código e na inovação, sem a carga de gerenciar servidores, armazenamento, rede e sistemas operacionais.

Exemplo no Azure: Azure App Service é um exemplo de PaaS que permite aos desenvolvedores construir, implantar e escalar aplicações web e APIs rapidamente, com suporte a múltiplas linguagens de programação, como .NET, .NET Core, Java, Ruby, Node.js, PHP ou Python.

Responsabilidade da Azure: além da infraestrutura física, a Microsoft também gerencia a plataforma, incluindo sistemas operacionais, serviços de rede e capacidades de runtime. Isso significa que a segurança do sistema operacional e certos aspectos da segurança da rede são gerenciados pela Azure.

Responsabilidade do cliente: os clientes são responsáveis pela segurança de suas aplicações, incluindo o código da aplicação, a gestão de identidades e acessos para a aplicação e a proteção dos dados da aplicação.

Referência: https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-paas/

## SaaS (Software as a Service)
Entrega aplicações completas e operacionais aos usuários finais através da internet. Com SaaS, os usuários não precisam se preocupar com a instalação, manutenção ou atualização do software; tudo é gerenciado pelo provedor de serviços. Os usuários acessam o software via navegador web ou aplicativos, geralmente sob um modelo de assinatura.

Exemplo no Azure: Microsoft Office 365 é um exemplo de SaaS, oferecendo um conjunto de aplicações de produtividade (como Word, Excel, PowerPoint e Outlook) hospedadas na nuvem, permitindo aos usuários acessar, colaborar e armazenar documentos online.

Responsabilidade do cliente: os clientes são principalmente responsáveis pela gestão de suas contas e identidades, além da proteção dos dados que inserem nas aplicações SaaS.

Exemplo: ao usar o Microsoft Office 365, a Microsoft é responsável pela segurança da aplicação e da infraestrutura, enquanto o cliente deve gerenciar as permissões de acesso dos usuários e proteger os dados que são armazenados e processados pelo Office 365.

Referência: https://azure.microsoft.com/pt-br/resources/cloud-computing-dictionary/what-is-saas/
