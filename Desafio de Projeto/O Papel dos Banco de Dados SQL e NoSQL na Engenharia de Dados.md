# Projeto: O Papel dos Bancos de Dados SQL e NoSQL na Engenharia de Dados

**Um banco de dados é uma coleção organizada de grandes volumes de dados, normalmente armazenados eletronicamente em um sistema de computador. Um banco de dados geralmente é controlado por um sistema de gerenciamento de banco de dados (DBA), que é usado para armazenar e recuperar dados de forma ordenada.**

## Entendendo as diferenças e características entre Banco de Dados SQL e NoSQL:

**Bancos de dados relacional (SQL) é um banco de dados onde armazenamos dados com um relacionamento entre si. Usado quando se precisa de um sistema mais rígido, quando já se conhece que tipos de dados você vai relacionar.**

**NoSQL = No Only SQL (Não Apenas SQL) surgiu como uma alternativa ao SQL e não para tentar substituir. A necessidade veio principalmente por conta de escalabilidade (ter que armazenar cada vez mais informações e dados não estruturados). NoSQL veio para suprir o que os bancos relacionais não conseguiam.**

## Características do SQL

* **Estrutura bem definida: os bancos de dados SQL possuem uma estrutura bem definida, com tabelas e colunas predefinidas e um esquema de relação entre elas. Isso permite que os dados sejam organizados e gerenciados de forma estruturada.**

* **Suporte a transações: os bancos de dados SQL são projetados para suportar transações seguras, garantindo que todas as alterações feitas no banco de dados sejam consistentes e duráveis.**

* **Linguagem SQL: os bancos de dados SQL utilizam a linguagem SQL para manipulação e consulta de dados, o que torna o processo de consulta e atualização de dados mais fácil e intuitivo.**

* **Conformidade com padrões: os bancos de dados SQL seguem padrões internacionais, o que facilita a portabilidade dos dados e a interoperabilidade entre diferentes sistemas.**

* **Escalabilidade vertical: os bancos de dados SQL são escaláveis verticalmente, o que significa que é possível aumentar a capacidade de armazenamento e processamento do banco de dados adicionando recursos ao servidor que hospeda o banco de dados.**

* **Integridade dos dados: os bancos de dados SQL garantem a integridade dos dados armazenados, através da implementação de restrições de integridade referencial, chaves primárias, chaves estrangeiras, entre outras.**

* **Consistência dos dados: os bancos de dados SQL garantem a consistência dos dados armazenados, através da implementação de regras de validação de dados e restrições de integridade.**

* **Suporte a ACID: os bancos de dados SQL oferecem suporte completo às propriedades ACID (Atomicidade, Consistência, Isolamento e Durabilidade), o que garante que as transações sejam processadas de forma segura e confiável.**


**Um banco de dados relacional (RDB) é usado para armazenar dados em conjuntos de tabelas, linhas e colunas. Um RDB é capaz de estabelecer links, ou relacionamentos, entre informações juntando tabelas, o que facilita o entendimento e a obtenção de insights sobre as conexões entre vários pontos de dados. Principalmente todos os bancos de dados relacionais usam Structured Query Language (SQL) para acessar e manipular os dados armazenados no banco de dados.**

**Uma vantagem do modelo de banco de dados relacional é que ele fornece uma maneira intuitiva de representar dados e permite o acesso a pontos de dados relacionados. Outras vantagens incluem a conformidade com ACID, pois garante a validade dos dados independentemente de erros, falhas ou outros erros potenciais. É flexível e fácil de usar. Pode-se facilmente adicionar, atualizar ou excluir tabelas, relacionamentos e fazer outras alterações sempre que necessário, sem afetar a estrutura geral ou afetar os aplicativos existentes.**

**Esse método de armazenar informações em tabelas e criar um relacionamento entre elas pode ter algumas desvantagens. Por exemplo, pode dar origem a uma alta complexidade se os dados não puderem ser facilmente encapsulados em uma tabela. Além disso, uma vez que a quantidade de dados se torna massiva, o banco de dados precisa ser particionado em vários servidores, o que pode causar vários problemas, pois juntar tabelas que foram distribuídas em servidores distintos não é uma tarefa fácil.**

## Características do NoSQL

* **Escalabilidade: Os bancos de dados NoSQL são projetados para serem escaláveis horizontalmente, o que significa que eles podem lidar com grandes quantidades de dados e tráfego da web sem diminuir o desempenho.**

* **Flexibilidade de esquema: Os bancos de dados NoSQL são conhecidos por sua flexibilidade de esquema, permitindo que os dados sejam armazenados em um formato que não segue necessariamente um modelo rígido de tabela/relação.**

* **Alta disponibilidade: Os bancos de dados NoSQL são projetados para ter alta disponibilidade, o que significa que o sistema continua a funcionar mesmo em caso de falhas de hardware ou software.**

* **Consistência eventual: Alguns bancos de dados NoSQL são projetados para ter consistência eventual, o que significa que as atualizações podem levar algum tempo para se propagar para todos os nós de dados, o que pode levar a dados desatualizados em alguns casos.**

* **Suporte a dados não estruturados: Os bancos de dados NoSQL são frequentemente usados para armazenar dados não estruturados, como documentos, imagens, vídeos e outras mídias.**

* **Distribuição: Os bancos de dados NoSQL são projetados para lidar com dados distribuídos em vários servidores ou data centers.**

* **Performance: Os bancos de dados NoSQL são geralmente capazes de fornecer alto desempenho em relação aos bancos de dados relacionais, especialmente em operações de leitura/gravação em grande escala.**

**O NoSQL é um tipo de banco de dados não relacional que difere do modelo relacional em vários aspectos. Em primeiro lugar, ele não usa uma estrutura de tabelas com colunas e linhas para armazenar dados, mas sim uma variedade de estruturas diferentes, como documentos, grafos, pares chave-valor, colunas largas, entre outras. Essas estruturas são projetadas para lidar com diferentes tipos de dados, como texto, imagem, áudio e vídeo, o que os torna muito flexíveis e escaláveis.**

**Uma das principais vantagens do NoSQL é sua escalabilidade horizontal, o que significa que é possível adicionar mais servidores para aumentar a capacidade de armazenamento e processamento de dados sem afetar a performance. Além disso, ele também é mais adequado para lidar com grandes volumes de dados não estruturados e semi-estruturados, como os gerados por aplicativos web, redes sociais e sensores.**

**Outra característica do NoSQL é a sua flexibilidade em relação aos esquemas. Enquanto nos bancos de dados relacionais é necessário definir um esquema rígido antes de inserir os dados, nos bancos de dados NoSQL é possível inserir dados sem a necessidade de uma definição prévia, permitindo uma maior agilidade no desenvolvimento e evolução dos sistemas.**

**No entanto, essa flexibilidade pode levar a problemas de consistência de dados em casos de atualizações simultâneas, o que é conhecido como "problema de concorrência". Além disso, a falta de um modelo padronizado pode dificultar a integração com outros sistemas e ferramentas que usam SQL.**

**Em resumo, o NoSQL é uma opção interessante para sistemas que lidam com grandes volumes de dados não estruturados e que precisam de alta escalabilidade, mas é importante considerar suas limitações em termos de consistência e integração com outros sistemas que utilizam SQL.**

## Conclusão

**Tanto os bancos de dados SQL quanto os NoSQL têm vantagens e desvantagens. O SQL é mais estruturado e rígido, o que o torna mais consistente e organizado. O NoSQL, por outro lado, é mais flexível e escalável, permitindo o armazenamento de grandes volumes de dados não estruturados e complexos. A escolha do modelo de banco de dados adequado depende das necessidades específicas de cada projeto, incluindo o tipo e volume de dados a serem armazenados, a escalabilidade necessária e os requisitos de integridade e consistência dos dados.**


```python

```
