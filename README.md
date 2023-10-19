# Bem-vindo(a) ao ConnectIF!

O ConnectIF é uma rede social desenvolvida por estudantes para estudantes , com o objetivo auxiliar na conexão e inclusão de alunos do IFRS Campus Feliz.

A rede social está sendo desenvolvida na disciplina Tópicos Avançados em Informática, no 3º trimestre do ano de 2023.

## Problema:

- Criar conexões com os (as) colegas e participar de um grupo de amigos (as) são alguns dos fatores apontados como relevantes para o sucesso escolar. Muitas pessoas que ingressam nos cursos técnicos do IFRS não conhecem ninguém na turma, algumas são tímidas e com isso apresentam maior dificuldade para se entrosar. Como podemos ajudá-las?

## Sobre a atividade:

- Neste trimestre a turma de Tópicos Avançados em Informática desenvolverá três soluções para um problema a partir do desenvolvimento de software. Para isso, serão formadas equipes de acordo com a afinidade e a necessidade a partir da demanda. Como resultado, ao final do trimestre será disponibilizado um software produzido pela turma para as demais pessoas que compõem o nosso campus.

- 

## Dinâmica:

- A turma será dividida em três grupos com liberdade para definir como será realizada a divisão de tarefas, desde que todas as pessoas tenham responsabilidades equivalentes e participem de todas as etapas. O grupo deverá acompanhar o cronograma de entregas e se organizar para cumprí-lo. Ao final de cada aula deve ser registrado de forma individual no diário disponibilizado no Moodle qual foi a sua contribuição para o desenvolvimento do projeto.

## Cronograma:

| Data             | Entrega                                                                       |
| ---------------- | ----------------------------------------------------------------------------- |
| 14/09            | Definição do projeto e apresentação de plano de atividades nomeadas no Trello |
| 21/09            | Escolha do protótipo de telas                                                 |
| 28/09            | Desenvolvimento                                                               |
| 5/10, 6/10, 7/19 | Mostra Técnica                                                                |
| 19/10            | Desenvolvimento                                                               |
| **26/10**        | **Avaliação Parcial**                                                         |
| 9/11             | Desenvolvimento                                                               |
| 16/11            | Desenvolvimento                                                               |
| 23/11            | Desenvolvimento                                                               |
| 30/11            | Realização de testes e correções                                              |
| **7/12**         | **Avaliação Final**                                                           |

## Avaliação:

A avaliação será individual e irá ocorrer em dois momentos:

- **Avaliação Parcial (peso 4):**
  - Apresentação para o professor do desenvolvimento e do que foi realizado por cada pessoa do grupo.
- **Avaliação Final (peso 6):**
  - Apresentação para a turma com suporte de slides e demonstração.

## Para rodar a aplicação:

Para testar a nossa rede social, você deve clonar o [front-end]("https://github.com/ConnectIFRS/front-end") e o [back-end]("https://github.com/ConnectIFRS/back-end") e deve garantir que tenha o [Node]("https://nodejs.org/en") instalado em sua máquina.
Em seguida, no front-end, basta rodar o comando:

```sh
cd connectif/
```

e no back-end o comando:

```sh
cd server/
```

Com estes comandos, você entra no diretório raiz de cada projeto. Ao cumprir este passo, você pode rodar o comando:

````
```sh
npm install
````

e em seguida:

```sh
npm run dev
```

Estes comandos servem para ambos os projetos. Caso deseje visualizar o banco de dados, crie uma nova aba do terminal, entre no diretório `server` no back-end e execute o comando `npx prisma studio`. Este comando abrirá uma nova aba no seu navegador mostrando todas as informações armazenadas no uso da aplicação.

## Sobre os criadores:

[Camila Ehrig Zandoná](https://github.com/camilazan14);

[Jéssica Hahn](https://github.com/candyycat);

[Marcelo José Griebler Ost](https://github.com/marceloost);

[Matheus Persch](https://github.com/DevTheusP);

[Otávio João Maldaner](https://github.com/OtavioMaldaner);

**Feliz - RS | 19/10/2023**
