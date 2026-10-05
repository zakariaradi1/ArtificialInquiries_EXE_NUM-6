# Diagramme de classes : sélection des tâches

```mermaid
classDiagram
    class CoreTask {
        +int position
        +boolean delegation
        +boolean completeTrust
        +boolean hesitation
        +String reasoning
    }

    class Task {
        +String id
        +String description
        +Category category
    }

    class Category {
        <<enumeration>>
        BUSINESS
        PLEASURE
        BUSINESS_PLEASURE
    }

    CoreTask --> Task : sélectionne
    Task --> Category : appartient à
```
