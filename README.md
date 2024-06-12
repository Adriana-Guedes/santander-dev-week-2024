# Bootcamp Santander 2024


Publicando Sua API REST na Nuvem Usando Spring Boot 3, Java 17 e Railway.


## Diagrama de Classes

```mermaid

classDiagram
    class User {
        +String name
    }

    class Account {
        +String number
        +String agency
        +String balance
    }

    class Feature {
        +String icon
        +String description
    }

    class Card {
        +String number
        +float limit
    }

    class News {
        +String icon
        +String description
    }

    User --> Account : has
    User --> Feature : has many
    User --> Card : has
    User --> News : has many

```

