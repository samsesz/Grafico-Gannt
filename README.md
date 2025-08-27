# Grafico-Gannt

```mermaid
flowchart TD
 
A(["Inicio"])
A --> B{"Faca uma escolha"}
B --> C["OP1"]
B --> D["OP2"]
B --> E["OP3"]
```
 
```mermaid
graph TD;
A[Inicio] --> B{Nota >6};
B --> |SIM| C[Aprovado];
B --> |NAO| D[Reprovado];
```
```mermaid
gantt
  title Exemplo de Grafico de Gantt
  dateFormat YYYY-MM-DD
  section 1ºSemestre
  1º Bimestre Finalizado:a1, 2025-02-02, 60d
  2º Bimestre Finalizado:a2, after a1, 60d
  section 2º Semestre
  3º Bimestre em Andamento: a3, 2025-08-01, 60d
  4º Bimestre em Andamento: a4, after a3, 60d
```
