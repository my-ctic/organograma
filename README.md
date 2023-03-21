# Organograma

- [GitHub](https://github.com/my-ctic/organograma)

<br>

O presente repositório visa apresentar o organograma do CTIC, conforme [Resolução 1482/2022](./docs/2022.05.27%20-%20Resolu%C3%A7%C3%A3o%201482.pdf), além de aprender como montar diagramas usando o [**Mermaid**](https://mermaid.js.org/).

```mermaid
flowchart LR
    0[CTIC] --> A[Área de Sistema de Informação]
    A[Área de Sistema de Informação] --> |DSI|A1[Diretoria de Sistemas de Informação]
    A[Área de Sistema de Informação] --> |DSAM|A2[Diretoria de Sistemas de Atividade-Meio]
    A[Área de Sistema de Informação] --> |DSAF|A3[Diretoria de Sistemas de Atividade-Fim]
    A[Área de Sistema de Informação] --> |DGICD|A4[Diretoria de Gestão de Informação e Ciência de Dados]
    A[Área de Sistema de Informação] --> A5[Corpo de Apoio Técnico]

    0[CTIC] --> B[Área de Infraestrutura e Operações]
    B[Área de Infraestrutura e Operações] --> B1[Diretoria de Infraestrutura e Operações]
    B[Área de Infraestrutura e Operações] --> B2[Diretoria de Redes e Telecom, integrada por Subárea de Apoio Técnico de Telefonia]
    B[Área de Infraestrutura e Operações] --> B3[Diretoria de Gestão de Ambiente Computacional]
    B[Área de Infraestrutura e Operações] --> B4[Corpo de Apoio Técnico de Segurança da Informação]
    B[Área de Infraestrutura e Operações] --> B5[Corpo de Apoio Técnico de Banco de Dados]
    B[Área de Infraestrutura e Operações] --> B6[Subárea de Apoio Técnico de Operações]

    0[CTIC] --> C[Área de Planejamento e Gestão]
    C[Área de Planejamento e Gestão] --> C1[Diretoria de Planejamento e Gestão]
    C[Área de Planejamento e Gestão] --> C2[Corpo de Apoio Técnico]
    C[Área de Planejamento e Gestão] --> C3[Subárea de Apoio Técnico-Administrativo]


    0[CTIC] --> D[Área de Suporte Técnico]
    D[Área de Suporte Técnico] --> D1[Diretoria de Suporte Técnico]
    D[Área de Suporte Técnico] --> D2[Corpo de Apoio Técnico]
    D[Área de Suporte Técnico] --> D3[Subárea de Apoio Administrativo de Atendimento ao Usuário]
    D[Área de Suporte Técnico] --> D4[Subárea de Apoio Administrativo de Suporte a Sistemas]
```

<br>

---

### Referências

- [**Mermaid Documentation**](https://mermaid.js.org/intro/)
- [Stackoverflow: **Spaces in Mermaid**](https://stackoverflow.com/questions/54311261/spaces-in-mermaid)
- [GitHub: **Include diagrams in your Markdown files with Mermaid**](https://github.blog/2022-02-14-include-diagrams-markdown-files-mermaid/)
- [Sec. Fazenda: hierarquia](http://www.fazenda.sp.gov.br/ua/hierarquia3.asp?ua1=0093022)

<br>

---

### Outros

- [Setor voltado à ciência de dados entra em funcionamento no CTIC](https://mpsp.mp.br/w/setor-voltado-%C3%A0-ci%C3%AAncia-de-dados-entra-em-funcionamento-no-ctic)
