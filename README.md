```
graph TD
    A[nome-do-seu-blog/] --> B{src/};
    A --> C[angular.json];
    A --> D[package.json];
    A --> E[tsconfig.json];

    B --> F{app/};
    B --> G{assets/};
    B --> H{environments/};
    B --> I[index.html];
    B --> J[main.ts];
    B --> K[polyfills.ts];
    B --> L[styles.css];

    F --> M{components/};
    F --> N{services/};
    F --> O[app-routing.module.ts];
    F --> P[app.module.ts];
    F --> Q[app.component.ts];
    F --> R[app.component.html];
    F --> S[app.component.css];

    M --> T{post-list/};
    M --> U{post-detail/};
    M --> V{post-create/};

    T --> T1[post-list.component.ts];
    T --> T2[post-list.component.html];
    T --> T3[post-list.component.css];

    U --> U1[post-detail.component.ts];
    U --> U2[post-detail.component.html];
    U --> U3[post-detail.component.css];

    V --> V1[post-create.component.ts];
    V --> V2[post-create.component.html];
    V --> V3[post-create.component.css];

    N --> N1[post.service.ts];

    G --> G1{data/};
    G1 --> G11[posts.json];
```
