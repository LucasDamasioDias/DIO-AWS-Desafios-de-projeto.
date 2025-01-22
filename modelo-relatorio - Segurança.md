# RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 22/01/2025
Empresa: Abstergo Industries 
Responsável: Lucas Damásio Dias

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Lucas Damásio Dias. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de aumentar a segurança na empresa.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: 
- Após a criação da conta root, implementar a autenticação multifator (MFA) para aumentar a segurança. Recomenda-se o uso de um aplicativo autenticador (como Google Authenticator ou Authy) ou uma chave de segurança física (como YubiKey), garantindo que apenas usuários autorizados possam acessar a conta root. Lembrando que a AWS não utiliza recursos do Google, mas permite a configuração do MFA (Multi-Factor Authentication) com aplicativos de terceiros, como Google Authenticator, Authy, Microsoft Authenticator, entre outros. A autenticação multifator na AWS pode ser configurada por meio de dispositivos virtuais (apps de autenticação) ou dispositivos físicos, como chaves de segurança compatíveis com FIDO2 (ex.: YubiKey) e tokens MFA da própria AWS.

Medida 2: 
- Armazenar as credenciais da conta root em local seguro e criar uma conta Master para uso cotidiano. Essa conta deve possuir permissões essenciais para a operação da empresa, aplicando o princípio de privilégio mínimo. Os acessos críticos devem ser restritos e utilizados apenas quando estritamente necessário, reduzindo riscos de exposição.

Medida 3: 
- Criação e gerenciamento dos grupos IAM. Os grupos deverão ser criados com o mínimo de acesso possível não extrapolando as suas funções. Usuários de grupos diferentes mas com a necessiadade das políticas de outros grupos deverão ser inclusos nos devidos grupos. Com o tempo o projeto deverá ser escalado para a criação das Roles necessárias.


## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado a melhoria de segurança através de uma devida implementação o IAM e do MFA, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

Assinatura do Responsável pelo Projeto:

Lucas Damásio Dias