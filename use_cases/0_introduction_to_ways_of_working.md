# Introduction

```mermaid
flowchart TD
    A[GP Surgeries] ==>|Primary care data| B[London Data Service]
    Ab[NHS Digital] ==>|Commissioning datasets| B
    Ac[Local data sources] ==>|ICS data| E
    Ad[NHS Trust CogStacks] ==>|Unstructured Hospital data| B
    B ==>|Linked data| C[NWL Research/Analytics Environment]
    Ae[AIC FLIP] ==> |Multi-modal data (imaging metadata)| C
    Ae[AIC FLIP] ==> |Hospital cancer data| B
    B ==>|Linked data| E[NCL Integrated Care Board Sandpit]
    B ==>|Linked data| E[NEL Integrated Care Board Sandpit]
    B ==>|Linked data| E[NWL Integrated Care Board Sandpit]
    B ==>|Linked data| E[SEL Integrated Care Board Sandpit]
    B ==>|Linked data| E[SWL Integrated Care Board Sandpit]
    C ==>|Linked data| F[Research environments]

    classDef blue fill:#89c, stroke-width:0px
    class A,Ab,Ac blue
```
