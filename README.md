![Geek Devs](https://geekdevs.com.br/images/logo.png 'GeekDevs')

# Geek Devs FRONT-END desafio para team frontend

**Geek Devs**: Somos uma fábrica de software focada em engenharia e qualidade com a utilização de metodologias ágeis. Transformamos ideias em código.

Trabalhamos com pessoas que são apaixonadas por tecnologia, formando uma grande equipe de engenheiros e clientes valiosos.

## Quem queremos em nossa equipe

Damos as boas-vindas a pessoas altamente qualificadas que desejam construir produtos incríveis e terão o orgulho de mostrá-los aos seus amigos e familiares! Também estamos procurando engenheiros iniciantes que queiram aprender e praticar o desenvolvimento de software usando as melhores práticas utilizadas por muitos participantes do mercado.

## O que terá nesse desafio?

É destinado a todos os candidatos, independentemente da experiência

Depois que você terminar, revisaremos seu código, forneceremos feedback e seguiremos para as próximas etapas da seleção.

## Algumas dicas

É natural sentir-se estressado durante um teste, então não entre em pânico. Anotamos algumas dicas boas e velhas que podem acalmá-lo:

- [ ] Relaxe mentalmente e fisicamente
- [ ] Considere soluções alternativas
- [ ] Se você estiver travado, respire, vai se divertir e comece novamente
- [ ] Planeje antes de começar
- [ ] Mantenha o quadro geral em mente

## Vamos começar

Vamos fingir que lançamos uma plataforma de avaliação de cursos online e gostariamos que os usuários favoritem :heart: os nossos cursos.

Seu primeiro objetivo como desenvolvedor front-end é nos ajudar a expandir nossa plataforma, construindo os primeiros componentes visuais e página web.

## Requisitos de Desenvolvimento

### Quais tecnologias posso usar?

- Node
- React
- ES6+
- React Hooks

Você também pode usar o <a href="https://create-react-app.dev/docs/getting-started/" target='_blank'>create-react-app</a> se quiser.

## Primeiro Passo

É hora do show! Lembre-se, crie componentes essenciais para cada parte reutilizável de seu aplicativo, como listas de nós e informações detalhadas.

Vamos conectar todos eles e criar as páginas web:

- exibir todas os cursos com suas devidas informações resumidas em uma lista, filtrando e pesquisando.
- clique em cada curso e abra os detalhes do curso (todos atributos)
- faça o CRUD para cadastro dos cursos seguindo a API do `json-server` 
- exibir todos os usuários e os seus cursos favoritados
- clique em cada curso e abra os detalhes do usuário (todos atributos)
- simule que um usuário favoritou o curso  clicando em :heart: e aparecendo uma mensagem do tipo "Você favoritou o curso... bla bla bla"

## Segundo Passo

- Não há thumbnail no banco de dados da API, portanto, gostaríamos de ver como você implementa uma estratégia de thumbnail fake


## Terceiro Passo

Seria ótimo ver essas bibliotecas sendo usadas em seu código, mas adoraríamos saber o que você pode sugerir para nós:

- Uma página da web de login falsa usando uma estratégia de token JWT (não precisa de backend, somente salve a sessão com um token falso) - http://jwt.io/ 
- Conjunto de ícones vetoriais - https://fontawesome.com/ 
- Material UI - https://material-ui.com/pt/

## Quais são os principais aspectos que iremos avaliar no seu código:

- Código limpo
- Componentização
- Responsividade
- Quão longe você pode passar pelo desafio

## Estrutura

Utilize <a href='https://www.npmjs.com/package/json-server' target='_blank'>json-server</a> para simular o backend.

A estrutura do nosso banco:

```

{
  "courses" : [
    {
      "id": 1,
      "tiutle": "Title Course 1",
      "price" : 10.40,
      "workland": 44,
      "lesson": 10,
      "author": "Name author 1",
      "year": 2020
    },
    {
      "id": 2,
      "tiutle": "Title Course 2",
      "price" : 1.50,
      "workland": 44,
      "lesson": 20,
      "author": "Name author 2",
      "year": 2020
    },
    {
      "id": 3,
      "tiutle": "Title Course 3",
      "price" : 1.50,
      "workland": 44,
      "lesson": 20,
      "author": "Name author 3",
      "year": 2020
    }
  ],

  "users": [
    {
      "id": 1,
      "name": "Name User",
      "email": "teste[a]teste.com.br",
      "favorites" : [
        {
          "id": 1,
          "tiutle": "Title Course 1",
          "price" : 10.40,
          "workland": 44,
          "lesson": 10,
          "author": "Name author 1",
          "year": 2020
        },
        {
          "id": 3,
          "tiutle": "Title Course 3",
          "price" : 1.50,
          "workland": 44,
          "lesson": 20,
          "author": "Name author 3",
          "year": 2020
        }
      ]
    }
  ]
}



```

## Como nos enviar

Crie um repositório privado no github e coloque os seguintes usuários como colaboradores: `Wil-g2` e `matheusflauzino`







