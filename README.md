Sistema de Cadastro de Pessoas

O Objetivo do Projeto
O PeopleRegister é uma aplicação web simples e responsiva desenvolvida para a gestão e cadastro de informações de pessoas, incluindo dados pessoais e profissionais. O objetivo principal é fornecer uma interface de usuário intuitiva para realizar operações de criação, leitura e remoção em tempo real, utilizando armazenamento persistente.

Descrição das Funcionalidades
A aplicação oferece as seguintes funcionalidades principais:
Cadastro de Pessoas: Permite adicionar novas pessoas preenchendo o nome completo, e-mail, data de nascimento, cargo e status (Ativo/Inativo).
Cálculo de Idade: Calcula e exibe a idade da pessoa dinamicamente com base na data de nascimento fornecida.
Listagem em Tempo Real: Exibe todas as pessoas cadastradas em uma tabela, com atualização instantânea (real-time) de dados.
Remoção de Registros: Permite remover registros diretamente da tabela.
Persistência de Dados: Todos os dados são salvos de forma segura no banco de dados Firebase Firestore.
Design Responsivo: O layout é otimizado para funcionar perfeitamente em dispositivos móveis, tablets e desktops.

Tecnologias Utilizadas
Este projeto foi construído inteiramente em um único arquivo HTML, utilizando tecnologias web padrões e o Firebase para o backend:
HTML5: Estrutura semântica do aplicativo.
JavaScript: Lógica de manipulação do DOM, validação de formulários e interação com o banco de dados.
Tailwind CSS: Framework utilitário para estilização e garantia de um design totalmente responsivo e moderno.
Firebase/Firestore: Utilizado como banco de dados NoSQL em tempo real para armazenamento persistente e seguro dos registros de pessoas.

Instruções para Execução do Projeto
Como este projeto é um aplicativo Single-Page Application (SPA), ele é extremamente simples de executar:

git clone:  https://github.com/seu-usuario/people-register-app

Abra o Arquivo:
Simplesmente abra o arquivo index.html em qualquer navegador moderno (Chrome, Firefox, Edge, etc.).A aplicação será carregada imediatamente e se conectará automaticamente ao Firebase Firestore para gerenciamento de dados. Não é necessário configurar um servidor local.
