```mermaid
stateDiagram-v2
FMS --> Router/Field_Access_Point
Red_Switch --> [*]
Still --> Moving
Moving --> Still
Moving --> Crash
Crash --> [*]
```
