# Modelo-Booleano

Esse repositório prové a <b>implementação do modelo booleano clássico </b>para <b>recuperação da informação</b>. O problema da recuperação da informação consiste em decidir em uma coleção de documentos, qual a relevância de cada documento. O modelo consiste em como o documento será visto pelo algoritmo que faz essa classificação. No modelo booleano um documento é representado por um conjunto de termos de indexação que podem ser definidos de forma intelectual (manual) por profissionais especializados ou automaticamente, utilizando algoritmos computacionais.
As buscas são formuladas por meio de uma expressão booleana composta por termos ligados por operadores lógicos AND, OR e NOT e apresentam
como resultado os documentos cuja representação satisfazem às restrições lógicas da expressão de busca.


```javascript
Javascript AND linguagem OR dsafdsafdsaf
[
  'JavaScript',      'linguagem',        'programação',
  'permite',         'implementar',      'funcionalidades',
  'complexas',       'páginas',          'momento',
  'página',          'web',              'apenas',
  'mostrar',         'informações',      'estáticas',
  'elas',            'mostram',          'real',
  'conteúdos',       'mapas',            'animações',
  'gráficas',        'apostar',          'Javascript',
  'provavelmente',   'aprendizadoSeção', 'Javascript',
  'tão',             'fácil',            'aprender',
  'HTML',            'outros',           'pilares',
  'desenvolvimento', 'Antes',            'aprender',
  'altamente',       'recomendável',     'aprenda',
  'menos',           'estas',            'duas',
  'Você',            'começar',          'Começando',
  'Web',             'Introdução',       'HTML',
  'Introdução',      'CSS',              'Possuir',
  'experiência',     'outras',           'linguagens',
  'programação',     'serão',            'Depois',
  'aprender',        'básico',           'apto',
  'estudar',         'tópicos',          'JavaScript',
  'ensinado',        'Guia',             'JavaScript',
  'Referências',     'API',              'Web'
]
[
  'dsafdsafdsaf',
  'sdfa',
  'dfsaf',
  'dsaf',
  'dsafdsafdsaf',
  'safdsa',
  'fdsaf',
  'sdafdsafdsafdsafdsafdsafdsafdsafdsafdsafdsafdsfdas',
  'fdsaf',
  'dsafdsafdsafdsafdsa',
  'sdfafsdafdsafsdf'
]
arquivosRelevantes:  [ '1.txt', '2.txt' ]
```


## Requisitos para executar o projeto

Para executar o projeto é necessário: 

<ul>
  <li> A plataforma Javascript <a href="https://nodejs.org/en/">nodejs</a></li>
  </ul>
  
  
 ## Forma de uso
 
 Antes de executar o node é necessário instalar as dependências do projeto, para tanto basta usar:
 
 ```bash
 npm install
 ```
 
 Depois disso basta executar o arquivo principal do projeto ``code.js`` da seguinte forma:
 
 ```bash
  node .\code.js
 ```
 
 Depois dessa execução o programa aguardará entradas para a query de busca, então você digita a query de busca que precisa, por exemplo 
 na query ``Javascript AND linguagem OR dsafdsafdsaf`` será feito:
 
 ```javascript
 Digite a query de busca: exemplo:     Javascript AND bananas AND(tomates AND morangos)
Javascript AND linguagem OR dsafdsafdsaf
[
  'JavaScript',      'linguagem',        'programação',
  'permite',         'implementar',      'funcionalidades',
  'complexas',       'páginas',          'momento',
  'página',          'web',              'apenas',
  'mostrar',         'informações',      'estáticas',
  'elas',            'mostram',          'real',
  'conteúdos',       'mapas',            'animações',
  'gráficas',        'apostar',          'Javascript',
  'provavelmente',   'aprendizadoSeção', 'Javascript',
  'tão',             'fácil',            'aprender',
  'HTML',            'outros',           'pilares',
  'desenvolvimento', 'Antes',            'aprender',
  'altamente',       'recomendável',     'aprenda',
  'menos',           'estas',            'duas',
  'Você',            'começar',          'Começando',
  'Web',             'Introdução',       'HTML',
  'Introdução',      'CSS',              'Possuir',
  'experiência',     'outras',           'linguagens',
  'programação',     'serão',            'Depois',
  'aprender',        'básico',           'apto',
  'estudar',         'tópicos',          'JavaScript',
  'ensinado',        'Guia',             'JavaScript',
  'Referências',     'API',              'Web'
]
[
  'dsafdsafdsaf',
  'sdfa',
  'dfsaf',
  'dsaf',
  'dsafdsafdsaf',
  'safdsa',
  'fdsaf',
  'sdafdsafdsafdsafdsafdsafdsafdsafdsafdsafdsafdsfdas',
  'fdsaf',
  'dsafdsafdsafdsafdsa',
  'sdfafsdafdsafsdf'
]
arquivosRelevantes:  [ '1.txt', '2.txt' ]
 ```
 
 Na saída ``aquivos relevantes`` fica apenas os documentos que são relevantes para a query escolhida.
 
 ## Quer saber como esse modelo foi desenvolvido??
 
 Tenho um tutorial que explica como construir esse modelo booleano em [Livro-RiJS](https://github.com/SergioNoivak/Livro-RiJS)
 
 
 ## Dúvidas??
 Me mande um email em serginhosnovak@hotmail.com, ou entre em contato comigo via redes sociais: Sergio Souza Novak.

