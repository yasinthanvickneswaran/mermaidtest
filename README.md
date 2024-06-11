```mermaid
%%{init: { 'logLevel': 'debug', 'theme': 'base', 'timeline': {'disableMulticolor': true}}}%%
  timeline
    title Timeline of C.Elegans Connectomics Data
    1986 : White A
    1987 : Durbin B
    2009 : Altun C
    2011 : Varshney D
    2015 : Pereira E
    2016 : Bentley F
    2019 : Cook G
    2020 : Fenyves H
         : Cook I
    2021 : Brittin J
         : Witvliet F
         : Taylor K
         : Yemini L
    2023 : Beets M
         : Atanas N
         : Randi O
```

```mermaid
flowchart TD
    c1-->a2
    subgraph Functional
    H["Fenyves et al. (2020)"]
    end
    subgraph Developmental
    b1-->b2
    end
    subgraph Extrasynaptic
    E["Pereira et al. (2015)"] --> F["Bentley et al. (2016)"]
    end
    subgraph Gene Expression
    C["Altun et al. (2009)"] --> 
    end
    subgraph Anatomical
    A["White et al. (1986)"] --> B["Durbin (1987)"]
    A --> D["Varshney et al.(2011)"]
    A --> G["Cook et al. (2019)"]
    A --> I["Cook et al. (2020)"]
    end
```
