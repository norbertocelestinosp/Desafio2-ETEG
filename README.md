# Desafio2-ETEG
Desafio 2 ETEG

Desafio – Desenvolvedor Fábrica 2021

OPÇÃO 2

● Implementar uma aplicação que consuma dados de alguma API pública REST,
à sua escolha.

Caso não tenha nenhuma em mente, usar a seguinte API:
http://dadosabertos.almg.gov.br/ws/prestacao_contas/contratos/pesquisa

Os parâmetros desta pesquisa são:
NOME - DESCRIÇÃO - TIPO
?cod= - Código do contrato. - Integer
?ano= - Ano do contrato. - Integer
?tipo= - Tipo de contrato: - String
● ‘Contrato’
● ‘Convênio’
?forn= - Nome do fornecedor. - String
?dota= - Dotação orçamentária. - String
?numLic= - Número do processo licitatório. - Integer
?anoLic= - Ano do processo licitatório - Integer
?modal= - Modalidade do contrato. - String
?numModalC
to = - Número da modalidade de contrato - Integer
?anoModalC
to = - Ano da modalidade de contrato - Integer

O formulário da página de pesquisa deve conter todos os campos de pesquisa
possíveis.

Exemplo de chamada na API:
http://dadosabertos.almg.gov.br/ws/prestacao_contas/contratos/pesquisa?ano=2017
&formato=json

Observações

● Utilizar alguma tecnologia frontend. Utilizar Angular ou React é um diferencial.
● Outras API’s disponíveis podem ser invocadas para enriquecer a aplicação.
Por exemplo, a API de fornecedores pode ser utilizada para auxiliar no
preenchimento do parâmetro “forn”.

O que será avaliado

● Estrutura do projeto: seleção e organização do ferramental mais adequado
(KISS);

● Qualidade do código: organização, uso semântico de tags, testes
automatizados se aplicável;

● Design da solução: o objeto retornado pela API possui centenas de atributos.
Será avaliado o formato que essas informações são apresentadas para o
usuário;

● Design da aplicação: usabilidade, criatividade, estilo. Uso adequado e
customização de folha de estilo existente, se aplicável, como bootstrap,
foundation,bulma, etc;

● Performance e compatibilidade: paginação e responsividade.

Entrega Versionar o código no GitHub e nos enviar por e-mail com o assunto: [TESTE FRONTEND] - <Seu nome aqui>.
