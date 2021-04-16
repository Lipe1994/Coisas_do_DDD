# Coisas_do_DDD
Minha lista de resumos teóricos de tópicos do DDD.

# Solid
[Ropositório onde escrevi um pouco de solid](https://github.com/Lipe1994/Solid)


# Ubiquitous language
Ubiquitous language, trata-se de manter uma linguagem comum, perceptível e que tenha os mesmos valores para todos os envolvidos dentro de um contexto. Isso faz com que todos falem a mesma língua.

# Modelagem estratégica
Para tornar o projeto autamente escalável, necessitamos de quebrar a aplicação em pedaços menores cada um com uma responsabilidade única.
Estes pedaços menores formam o Context Map(mapa de contextos).

# Bouded Context(Contexto Delimitado)
 Cada contexto deve ter um significado bem definido, além dos limites a linguagem muda pois cada contexto tem sua própria Ubiquitous language

# Tipos de relacionamento
Contextos Upstream influenciam contextos Downstream.

    Cliente => É um Downtream;

    Fornecedor => É um Upstream;

    Conformista => Relação em que um contexto Downstream se conforma com um serviço Upstream de terceiros;

    Camada de anti-corrupção => camada para garantir que mudanças no Upstream de terceiros não influencie na camada Downstream,
    de medo que se este serviço de terceiros for trocado não influencie  fora da camada de anticorrupção.


# Estilos e padrões de arquiterura
    Transaction Script Pattern;
    Table Module Pattern;
    Domain Module;
    

    CQRS;
    Event Sourcing;
    Arquitetura Cebola;
    Arquitetura Hexagonal;


    Camada de apresentação;
    Camada de aplicação;
    Camada de domínio;
    Camada de infra-estrutura;

# Projetos

[Ropositório com implementação com foco no domínio](https://github.com/Lipe1994/Implementacao_com_foco_no_dominio)

