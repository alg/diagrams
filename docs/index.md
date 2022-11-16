# Sample

This is a sample page with the diagram.

```mermaid
flowchart

A --> B & C --> D
```

After the chart comes another:

```mermaid
classDiagram

class First
class Second
class Third

First ..> Second: depends on
First ..|> Third
Third --> Second
```
