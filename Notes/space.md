```mermaid
classDiagram
      RevelTek <|-- AI
      RevelTek <|-- Tech Consulting
      RevelTek <|-- Innovation
      RevelTek : Startup Company
      RevelTek : Bootstrapped
      RevelTek: NAICS 541511
      RevelTek: NAICS 541611
      class AI{
          Make AI Personas
          Consult Clients in AI
      }
      class Tech Consulting{
          -int sizeInFeet
          -canEat()
      }
      class Innovation{
          +bool is_wild
          +run()
      }
```

```mermaid
pie
"AI" : 50
"Tech" : 30
"Consulting" : 20
```
