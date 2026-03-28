# Escala de Show.Table

    ```mermaid
    flowchart LR
        A[Start] --> B{Is it working?}
        B -- Yes --> C[Great!]
        B -- No --> D[Debug]
    ```


 ```graphviz
    digraph G {
      rankdir=LR;
      node [style=filled, color="#11ff84", fontcolor="#000"];
      Start -> Process -> End;
      Process -> Start [style=dashed, label="Loop"];
    }
  ```
