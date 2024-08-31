# App Seguro Facil
SeguroFácil é um formulário dinâmico que adapta campos e validações conforme o tipo de seguro selecionado (Carro, Casa, Vida). Focado em uma experiência de usuário fluida e acessível, o projeto utiliza as melhores práticas de front-end para oferecer uma interface responsiva e intuitiva.

## Desafio: Criação de um Formulário Dinâmico com Validação Condicional
Contexto:
Você está desenvolvendo uma aplicação para uma corretora de seguros. O objetivo é criar um formulário de solicitação de cotação de seguro que seja dinâmico e responda às entradas do usuário. Dependendo do tipo de seguro selecionado (Carro, Casa ou Vida), o formulário deve exibir diferentes campos específicos para cada tipo e realizar validações customizadas.

## Requisitos:

- Seleção de Tipo de Seguro:

Crie uma seção do formulário onde o usuário pode selecionar o tipo de seguro (Carro, Casa, Vida).
Baseado na seleção, exiba dinamicamente os campos relevantes para cada tipo de seguro.

- Campos Dinâmicos:

Seguro de Carro: Exibir campos para "Modelo do Carro", "Ano de Fabricação", "Número do Chassi".
Seguro de Casa: Exibir campos para "Endereço", "Área em m²", "Valor da Casa".
Seguro de Vida: Exibir campos para "Idade", "Valor do Seguro", "Histórico Médico".

- Validação Condicional:

Implemente validações específicas para cada tipo de seguro. Por exemplo:
Para "Seguro de Carro", o "Ano de Fabricação" deve ser maior que 2000.
Para "Seguro de Casa", o "Valor da Casa" não pode ser menor que R$ 100.000,00.
Para "Seguro de Vida", a "Idade" deve estar entre 18 e 65 anos.

- UI/UX:

Mantenha a interface limpa e intuitiva, garantindo que o usuário entenda claramente quais informações são necessárias.
Utilize estilos e animações para mostrar/ocultar campos conforme a seleção do tipo de seguro, proporcionando uma experiência de usuário fluida.

- Acessibilidade:

Certifique-se de que o formulário seja acessível, utilizando tags semânticas apropriadas e suportando navegação por teclado.

- Teste de Integração:

Implemente testes unitários para as validações e testes de integração para garantir que o formulário funcione corretamente em diferentes cenários.

- Entregáveis:
Um repositório Git com o código do projeto.
Documentação explicando as decisões técnicas e como rodar o projeto localmente.
Testes unitários e de integração, com instruções para rodá-los.

- Dicas:
Utilize um framework moderno (React, Angular ou Vue.js) para a construção do formulário.
Considere o uso de uma biblioteca de formulários como Formik (para React) ou Vue Formulate (para Vue.js) para facilitar a construção e validação dos formulários.
Preste atenção à responsividade para garantir que o formulário funcione bem em diferentes dispositivos.

### Objetivo:
O objetivo deste desafio é avaliar sua habilidade em criar interfaces dinâmicas, lidar com validações condicionais e garantir uma boa experiência de usuário e acessibilidade.

Challenge nível Pleno By ChatGPT.
