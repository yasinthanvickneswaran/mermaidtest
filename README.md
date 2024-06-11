```mermaid
flowchart TD
    classDef anat stroke:#f00
    classDef gene stroke:#0f0
    classDef es stroke:#00f
    classDef func stroke:#ee82ee


    subgraph 1970-1980
    A1[<a href='https://google.com'>"Albertson & Thomson (1976)"</a>]:::anat
    end
    subgraph 1980-1990
    A & B
    end
    subgraph 1990-2000
    A2
    end
    subgraph 2000-2010
    C
    end
    subgraph 2010-2020
    D & E & E1 & E2 & F & G & H & I
    end
    subgraph 2020-2030
    J & K & L & M & N & P & NP
    end     


    E --> H["Fenyves et al. (2020)"]:::func
    E1["Serrano-Saiz et al. (2013)"]:::es --> H
    E2["Gendrel, Hobert & Atlas (2016)"]:::es --> H
    K["Witvliet et al. (2021)"]:::anat
    E["Pereira et al. (2015)"]:::es --> F["Bentley et al. (2016)"]:::es

    C["Altun et al. (2009)"]:::gene --> L["Taylor et al. (2021)"]:::gene
    L --> M["Yemini et al. (2021)"]:::gene
    M --> N["Beets et al. (2023)"]:::gene

    A(["White et al. (1986)"]):::anat --> B["Durbin (1987)"]:::anat
    A1 --> A
    A1 --> I
    A  --> A2["Hall & Russell (1991)"]:::anat
    A --> D["Varshney et al.(2011)"]:::anat
    B --> D
    A2 --> D
    A --> G["Cook et al. (2019)"]:::anat
    A --> I["Cook et al. (2020)"]:::anat
    A --> J["Brittin et al. (2021)"]:::anat
    A --> F
    D --> F
    A --> NP["Ripoll-Sanchez et al. (2023)"]:::es
    A1 --> NP
    F --> NP
    L --> NP
    K --> NP
    D --> NP
    A --> P["Randi et al. (2023)"]:::func
    L --> P
    N --> P
    K --> P
    NP --> P
    F --> P

    
    
```
