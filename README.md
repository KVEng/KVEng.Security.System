<div align="center">
  <h1>KVEng Security System</h1>
</div>

## Strcuture

```mermaid
flowchart LR
subgraph KEng Security System
  ksc0[KEng Security Controller   ]
  kse1[KEng Security EndPoint #1  ]
  kse2[KEng Security EndPoint #2  ]
  kse3[KEng Security EndPoint #3  ]
  kse4[KEng Security EndPoint ... ]
  kse5[KEng Security EndPoint #N  ]

  ksc0 -. Manage .-> kse1
  ksc0 -. Manage .-> kse2
  ksc0 -. Manage .-> kse3
  ksc0 -. Manage .-> kse4
  ksc0 -. Manage .-> kse5
end
```

---
Copyright &copy; 2022 KevinZonda Engineering. All rights reserved.
