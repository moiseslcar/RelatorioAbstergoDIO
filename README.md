# RelatorioAbstergoDIO
Relatório do Desafio de Projeto - Proposta de implementação do Sistema de uma Indústria Farmacêutica em nuvem AWS

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 18/07/2023
Empresa: Abstergo Industries 
Responsável: Moisés Luciano Carvalho

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Moisés Luciano Carvalho. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- [Nome da ferramenta]: EC2 - Elastic Compute Cloud
- [Foco da ferramenta]: Substituir os servidores físicos da empresa, bem como toda a infraestrutura que comporta o pleno funcionamento dos sitemas utilizados atualmente pela Farmacêutica Abstergo Industries.
- [Descrição de caso de uso]: Num promeiro momento, migrar a aplicação e banco de dados para instãncias EC2, devidamente dimensionadas conforme complexidade da aplicação.

Etapa 2: 
- [Nome da ferramenta]: Amazon EC2 AutoScaling
- [Foco da ferramenta]: Escala automaticamente a quantidade de cpu (EC2), em momentos de alta frequência de acesso à aplicação e dados do negócio.
- [Descrição de caso de uso]: Para o sistema normal com a aplicação e o BD, já replicados e seguros; momentos de muita venda e alta demanda de recursos computacionais, requerem o serviço de autoscaling para escalar horizontalmente a infraestrutura de instâncias que comportam o sistema. Assim, não há sobrecraga de uma ou mais cpu's, garantindo desempenho e performance no processamento de grandes quantidades de lançamentos de compras e transações, com eficiência, segurança e melhor controle de custos para a organização.

Etapa 3: 
- [Nome da ferramenta]: ELB - Elastic Load Balancing 
- [Foco da ferramenta]: Em conjunto com o AutoScaling, um balanceamento de carga automático para garantir a alta disponibilidade da aplicação.
- [Descrição de caso de uso]: Em momentos de pico da semana, com muita procura pelos parceiros revendedores e com AutoScaling implementado, nosso sistema em nuvem terá o balanceamento de carga, distribuindo de maneira inteligente a demanda de consumo dos recursos computacionais entre as instãncias provisionadas no momento, promovendo uma aplicação altamente disponível, garantindo a satisfação do cliente mais exigente.



## Conclusão
A implementação de ferramentas na empresa Abstergo Industries tem como esperado alta disponibilidade de recursos necessários nos momentos mais críticos (de maior procura e acesso), para uma transação fluída e de ótima experiência, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.



Responsável pelo Projeto:

Moisés Luciano Carvalho
