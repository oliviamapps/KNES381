flowchart LR
    A[Aerhm.]
    F1[F]
    I[I]
    R[R]
    E1[E]
    F2[F]
    L[L]
    E2[E]
    UE[UE]
    GH[GH]

    %% invisible links to keep letters aligned
    A --> F1 --> I --> R --> E1 --> F2 --> L --> E2 --> UE --> GH

    %% color definitions
    classDef greenText fill:#ffffff,stroke:#2ca02c,color:#2ca02c;
    classDef blueText fill:#ffffff,stroke:#1f77b4,color:#1f77b4;
    classDef redText fill:#ffffff,stroke:#d62728,color:#d62728;

    %% apply colors
    class A redText
    class F1,I,R,E1,F2,L greenText
    class E2,UE,GH blueText

