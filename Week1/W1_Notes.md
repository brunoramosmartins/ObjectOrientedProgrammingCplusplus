# Week 1: Text I/O and functions: the main menu, part 1

This week you will learn about the C++ edit, compile and run cycle, and text I/O.

**Learning Objective**

- Write, compile and run a C++ program that prints messages to the console
- Use the standard library to do text I/O in the console
- Use if statements to conditionally execute different parts of a program
- Use a while loop to repeatedly receive and respond to user input

## Welcome to Object Oriented Programming

Este é o primeiro curso da especialização, mas há outros quatro cursos a seguir. Se você está aqui para aprender sobre C++, está no lugar certo. O instrutor se apresenta e fala sobre sua abordagem ao ensinar programação. Ele também explica a estrutura da especialização e detalha o conteúdo e os objetivos do curso atual. O instrutor tem experiência em várias linguagens de programação e destaca os benefícios de aprender C++. Ele menciona que o curso ensinará a construir um exemplo completo de um sistema de negociação de criptomoedas em C++. A especialização consiste em cinco cursos, cada um abordando diferentes aspectos do C++. O curso atual tem como objetivo ensinar os alunos a escrever, compilar e executar programas em C++, usando a biblioteca padrão para entrada e saída de texto, criando funções simples, usando loops e declarações condicionais. O curso inclui vídeos, questionários, leituras e exercícios práticos. A avaliação é feita por meio de revisões por pares e questionários. A especialização é voltada para aqueles que desejam aprender programação orientada a objetos usando C++.

## Demonstrating the merkelsim currency exchange simulation

Nesta aula, o professor demonstra a plataforma de negociação que será desenvolvida ao longo de cinco unidades de aprendizado no curso. Ele explica conceitos básicos de negociação, como livro de ordens, pares de negociação, ofertas de compra e venda, carteira e mecanismo de correspondência. O vídeo também mostra como executar o programa e apresenta o código-fonte que será desenvolvido ao longo do curso. O objetivo é que, ao concluir os cinco cursos, os alunos entendam completamente como a plataforma de negociação funciona. Para aprofundar o assunto, sugere-se a leitura de literatura sobre negociação e programação em C++.

## Is C++ a low-level language?

Neste vídeo, o professor introduz a ideia de linguagens de alto e baixo nível, explicando que o C++ é uma linguagem de baixo nível. Ele explica que a diferença entre as duas está no nível de abstração do hardware subjacente. Linguagens de alto nível não se preocupam com os detalhes do funcionamento do hardware, enquanto linguagens de baixo nível têm acesso direto ao hardware. O professor menciona que o C++ é útil para sistemas críticos e em tempo real, pois permite um maior controle sobre o hardware. Ele pede aos alunos que discutam no fórum quais linguagens são de alto ou baixo nível. O vídeo resume o conceito de linguagens de alto e baixo nível e apresenta exemplos dessas linguagens.

## Writing our first program

Neste vídeo, aprendermos como escrever o primeiro programa em C++ e o professor explica o processo de compilação e linkagem para criar um código executável. Ele utiliza o editor Visual Studio Code e mostra como utilizar a biblioteca padrão do C++ para imprimir mensagens no console. O professor também explica as etapas de compilação, que envolvem a geração de código assembly e código objeto, e a etapa de linkagem, que conecta o código objeto a bibliotecas externas. O vídeo fornece uma visão geral do processo de compilação e linkagem em C++.

## How to compile a program in web-based Visual Studio Code

Neste vídeo, o professor mostra como escrever e compilar um programa usando o ambiente de desenvolvimento integrado (IDE) baseado em navegador disponível na plataforma Coursera. Ele explica como abrir o Visual Studio Code, criar um novo arquivo, escrever um programa simples em C++, salvar os arquivos e fazer o download deles para backup. O instrutor também demonstra como compilar e executar o programa usando o terminal. O vídeo fornece uma introdução básica ao ambiente de codificação baseado em navegador e suas funcionalidades.

## Print a list of options (menu)

Neste vídeo, é hora de começar a construir nosso sistema de simulação de troca de moeda. Vamos aprender como as trocas de moeda funcionam construindo uma nós mesmos. A primeira etapa é decidir quais são as opções que o usuário pode fazer. O sistema será baseado em console, com entrada e saída de texto. Vamos imprimir um menu que dará ao usuário uma lista de opções do que ele deseja fazer. As principais tópicos abordados são: funcionamento de trocas de moeda, ofertas e lances, carteiras e resolução de negociações.

## Receiving user input with the extraction operator

Nesta aula, aprendemos a fazer o menu funcionar através da entrada opcional do usuário e decidir o que fazer com base nisso. Utilizamos o operador de extração para ler os dados da entrada padrão (cin) e armazená-los em uma variável. Verificamos se o usuário digitou algo e exibimos a opção escolhida. Também exploramos como o sistema de leitura da biblioteca padrão trata diferentes tipos de entrada, como números inteiros, números de ponto flutuante e palavras. Concluímos que a entrada do usuário é robusta e, no próximo vídeo, aprenderemos a lidar com essa entrada e realizar diferentes ações com base no que foi digitado.

## If statements: conditionally printing responses to the user

Nesta aula, o professor continua trabalhando no menu e adiciona lógica para imprimir uma resposta diferente dependendo da opção escolhida pelo usuário. Ele utiliza declarações condicionais "if" para verificar a entrada do usuário e imprimir mensagens de erro ou informações relevantes. Em seguida, ele envolve todo o código em um loop "while" infinito para permitir interações contínuas com o sistema. O autor sugere adicionar uma opção de saída no menu para encerrar o loop.

## Let's experiment with std::cout and std::cin

Nesta aula, o professor fala sobre o uso do standard Cin e standard Cout em programas em C++. Ele menciona a dificuldade de obter entrada e saída em máquinas antigas, como a máquina de diferenças de Babbage. O professor explica que o std é um namespace que contém componentes prontos para uso, como funções e classes, da biblioteca padrão do C++. Ele mostra como incluir a biblioteca iostream para acessar o standard Cout, que é usado para imprimir mensagens na saída do console. Ele também menciona o standard Cin, que é usado para ler dados de entrada. O professor destaca a importância de tratar diferentes tipos de entrada de forma adequada. No geral, o vídeo fornece uma introdução ao uso do standard Cin e standard Cout em programas em C++.

## Write menu functions

Nesta aula, o professor explica como criar funções para cada opção de um menu. Ele mostra como organizar o código em funções separadas para facilitar a implementação de funcionalidades específicas. O professor demonstra como criar as funções e chama-las no código principal. Ele enfatiza a importância da separação de responsabilidades e menciona que as funções podem ser modificadas posteriormente.