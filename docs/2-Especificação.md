# Especificações Do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Contexto.md"> Documentação de Contexto</a></span>

> Apresente uma visão geral do que será abordado nesta parte do
> documento, enumerando as técnicas e/ou ferramentas utilizadas para
> realizar a especificações do projeto

## Personas

**Persona 1**

**Nome:** Mariana Souza\
**Idade:** 32 anos\
**Profissão:** Analista de Marketing\
**Perfil:** Mariana é casada, tem uma rotina corrida e adora praticidade. Costuma fazer compras online para economizar tempo, principalmente de roupas e produtos eletrônicos. Dá muita importância a avaliações de outros clientes antes de finalizar uma compra e prefere lojas que oferecem frete rápido e políticas de devolução facilitadas. Atualmente, está buscando um site confiável para comprar um novo smartphone com um bom custo-benefício.

**Persona 2**

**Nome:** João Mendes\
**Idade:** 40 anos\
**Profissão:** Pequeno empreendedor\
**Perfil:** João é dono de uma loja de artigos esportivos e está sempre em busca de fornecedores confiáveis para comprar produtos em grande quantidade. Ele prefere plataformas de e-commerce que ofereçam preços competitivos, opções de pagamento flexíveis e entrega rápida. Além disso, valoriza um bom atendimento ao cliente e suporte pós-venda. Atualmente, está pesquisando um marketplace que ofereça descontos para compras no atacado.

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

#### As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### REQUISITOS FUNCIONAIS

|ID    | Descrição do Requisito                                                                                            | Prioridade |
|------|-------------------------------------------------------------------------------------------------------------------|------------|
|RF-001| O sistema deve permitir que os usuários criem uma conta informando nome, e-mail, senha e endereço.                |      ALTA  | 
|RF-002| O sistema deve permitir que os usuários adicionem produtos ao carrinho de compras.                                |      MÉDIA |
|RF-03 | O usuário deve poder escolher um método de pagamento (cartão de crédito, boleto, Pix, etc.) e finalizar a compra. |      MÉDIA |




### REQUISITOS NÃO FUNCIONAIS

|ID     | Descrição do Requisito                                                                              |Prioridade |
|-------|-----------------------------------------------------------------------------------------------------|-----------|
|RNF-001| O sistema deve carregar as páginas em até 3 segundos para garantir uma boa experiência ao usuário.  |   MÉDIA   | 
|RNF-002| O sistema deve proteger as informações dos clientes por meio de criptografia e medidas de segurança.|   ALTA    | 


> Lembre-se que cada requisito deve corresponder à uma e somente uma característica alvo da sua solução. 

-------------------------------------------------------------------------------------------------------------------------------------------------------------------

## HISTÓRIAS DO USUÁRIO

>Lembrem-se de que as histórias de usuário correspondem aos requisitos funcionais, porém são descritas em um formato que ajuda a identificar a persona (o tipo de
> usuário que utilizará o sistema).
>*Por exemplo, se um requisito funcional diz que o sistema deve permitir o cadastro de usuários, a história do usuário pode ser:
>"Como um novo cliente, eu quero criar uma conta para salvar meus dados e facilitar futuras compras."*


Abaixo são apresentadas as histórias de usuário baseadas nos requisitos funcionais do **e-commerce**:

**História 1 – Cadastro e autenticação de usuários**

**Como** um cliente,\
**Eu quero** criar uma conta no site,\
**Para que** eu possa salvar meus dados e realizar compras de forma mais rápida no futuro.\

**História 2 – Processo de compra e pagamento**

**Como** um cliente,\
**Eu quero** adicionar produtos ao carrinho e finalizar minha compra com um método de pagamento seguro,\
**Para que** eu possa receber meus pedidos no meu endereço sem complicações.\


-------------------------------------------------------------------------------------------------------------------------------------------------------------------

## RESTRIÇÕES
>Uma restrição de software é uma limitação ou condição que deve ser considerada no desenvolvimento do sistema. Essas restrições podem ser técnicas, de negócio, >legais ou operacionais e influenciam como o software será projetado, implementado e utilizado.

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                                         |
|--|-------------------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre             |
|02| Não pode ser desenvolvido um módulo de backend                    |
|03| O sistema deve funcionar apenas dentro da rede interna da empresa.|


> Enumere as restrições à sua solução. Lembre-se de que as restrições
> geralmente limitam a solução candidata.
> 
> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
