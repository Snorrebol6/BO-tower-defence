# BO-tower-defence
```mermaid
graph TD
    A[start timer: 5 seconds] -->  
    B((spawn Enemy))-->C(enemy walks towards end of the road)
   C -->|Enemy killed| D[earns gold]
   C -->|Enemy reaches the end| E[live lost]
