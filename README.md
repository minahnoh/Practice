# Practice
```mermaid
flowchart TD
  A[start] --> B{Decision?}
  B -- Yes --> C[Do something]
  B -- No --> D[Do something else]
  C --> E[End]
  D --> E
  
