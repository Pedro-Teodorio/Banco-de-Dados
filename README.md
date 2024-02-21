# Banco de dados (Aula 01)

## Banco de dados relacionais

### Vantagens

#### Consistência de dados:

- Procura garantir que dados permaneçam precisosválidos e atualizadps

- A consistenência é mantida através de regras bem definidas que usam a premissa chaves estrangeiras

- A integridade de dados evita que sejam corrompidos ou modificados

- A aplicação das regras evita redundância de dados,duplicação e que os dados sejam corrompidos.

#### Manipulação e Recuperação de Dados:

- SGBD oferece método padronizado e direto para interação com banco de dados.

- A linguagem SQL é amplamente utilizada em gestão e consulta de bancos de dados relacionais.

- A padronização facilita a manipulação de dados.

- Controle de transações, otimização e consultas

#### Suporte

- Vasto suporte teorioco

- Oferece ferramentas robustas para modelagem,administração e otimização de
  dados

- Compativel com varias linguagens de programação facilitando a integração entre sistemas

- Oferece diversas bibliotecas de conexão compativeis com diversas linguagens( Cada linguagem possui bibliotecas específicas)

### Desvantagens

#### Restrições de desempenho:

- Operações complexas entre tabelas devido a estruturação
  podem afetar o desempenho das consultas ao banco de
  dados.

- A consulta através de várias combinações entre tabelas podem tornar as consultas mais lentas.

#### Custo

- O custo de manutenção de SGBD podem ser custosas.

#### Escalabilidade:

- Aumentar o número de servidores é uma tarefa complexa. Dificuldade de manutenção da integridade de dados e
  consistência.

- Dificuldade de ampliação de sistemas distribuídos devido ao particionamento de dados.

## Banco Não Relcionais

Banco de dados não apenas SQL utiliza conceitos de busca e armazenamento de dados sem, necessariamente, usar o conceito de tabelas.

- Surgiu em 1998 como uma opção para o armazenamento de
  dados semi estruturados e não estruturados.

- Os dados podem ser armazenados usando modelos como
  Colunas, grafos, chave-valor e documentos.

### Estruturas

#### Modelo de Colunas:

- As informações possuem suas
  próprias colunas podendo ser
  agrupadas em famílias

- Facilita o gerenciamento de
  grandes volumes de dados de
  forma simples e veloz.

- BD Apache Cassandra.

#### Modelo de Grafos:

- A pesquisa de dados usa como
  princípio o conceito de grafo que é
  uma estrutura orientada por arcos
  conectados por arestas

- Os dados são armazenados
  considerando os conteúdos e a
  relação existente entre eles.

- ArangoDB, Neo4J e o Titan.

#### Modelo Chave-valor:

- Trabalham com o conceito formado
  por chaves associadas a valores
  específicos.
- São muito flexíveis.
- Amazon DynamoDB.

#### Modelo Documento:

- Todos os dados são tratados como
  documentos

- São muito aplicados a dados não
  estruturados.

- MongoDB.

### Vantagens

#### Flexibilidade:

- Os dados são armazenados de forma intuitiva.

- A modelagem se aproxima de como são usados nosaplicativos.

#### Escalabilidade:

- Aplicações NoSQL são desenvolvidas com previsibilidade deaumento de demanda.

- Trabalham com grandes volumes de dados e cargas detrabalho intensivas.

- Facilidade de adição de novos servidores.

#### Desempenho:
- Oferecem alta velocidade na consulta de registros.
- Respostas a consultas são mais rápidas.
#### Flexibilidade de dados:
- Podem ser armazenados dados estruturados, semiestruturados e não estruturados.

- Permite o uso de formatos de estruturas de acordo com anecessidade (chave-valor, documento, colunas e grafos).

#### Custo e manutenção:
- Flexibilidade e escalabilidade reduzem a necessidade dealterações frequentes no banco de dados reduzindo tempo ecusto de manutenção.

### Desvantagens

#### Falta de padrões universais:
- Dificulta operações de migração.

- Vários modelos diferentes de dados.

#### Suporte:

- O suporte a transações seguras é comprometido.

- Falta de ferramentas e documentação específicas em algunsmodelos.
