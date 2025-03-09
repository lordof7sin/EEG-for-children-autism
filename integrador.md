'''mermaid
graph TD;
    A[Start] --> B[Investigación de tecnologías diseñadas para la captación de señales encefálicas];
    B --> C[Investigación de hardware y sensores relacionados];
    C --> D[Diseño de la placa de circuito impreso en EAGLE];
    D --> E[Adquisición de componentes pendientes];
    E --> F[Fabricación del PCB];
    F --> G[Ensamblaje de componentes en la PCB];
    G --> H[Colocación y soldadura de componentes electrónicos en la PCB];
    H --> I[Fase de prueba inicial: registro y procesamiento de datos de actividades electroencefalográficas];
    I --> J[Evaluación de resultados y ajustes en el sistema];
    J --> K{¿Resultados satisfactorios?};
    K -- No --> L[Ajustes y correcciones en hardware y software];
    K -- Sí --> M[Optimización del modelo de predicción y nuevas pruebas];
    L --> M;
    M --> N[Ajustes finales y detalles de presentación];
    N --> O[Preparación y exposición del proyecto con su documentación];
    O --> P[Completed];
