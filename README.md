# Api REST e RESTFul

A arquitetura de API REST (Representational State Transfer) é baseada em princípios como recursos, URIs, métodos HTTP e representações.

## Diferenças entre REST e RESTFul

REST (Representational State Transfer) é um estilo arquitetural para design de sistemas distribuídos, enquanto RESTful refere-se à implementação dos princípios REST. REST utiliza operações HTTP (GET, POST, PUT, DELETE) para manipular recursos, promovendo simplicidade e escalabilidade. RESTful, por sua vez, segue as diretrizes REST de maneira rigorosa, enfatizando URIs significativas, representação de recursos e a ausência de estado entre requisições, resultando em APIs mais intuitivas e eficientes. Em resumo, REST é o conceito, enquanto RESTful é a aplicação prática desses conceitos em serviços web.

## HTTP verbs
HTTP verbs são métodos utilizados em solicitações HTTP para indicar a ação a ser realizada em um recurso. Os principais verbos incluem GET (obter dados), POST (enviar dados), PUT (atualizar um recurso), DELETE (excluir um recurso) e outros. Para usar, escolha o verbo apropriado para a operação desejada e inclua-o na solicitação HTTP, geralmente no cabeçalho “method” para especificar a ação.

## HTTP Status Code

HTTP Status Code é um código numérico retornado pelo servidor em resposta a uma solicitação HTTP, indicando o resultado da operação. Os códigos são agrupados em cinco classes, como 2xx para sucesso, 4xx para erros do cliente e 5xx para erros do servidor. Eles ajudam na compreensão do estado da solicitação. Ao usar, examine o código recebido para determinar o resultado da solicitação.

---

Autor do resumo: Matheus José Pereira de Andrade - 01521951
