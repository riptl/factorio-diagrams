```mermaid
flowchart LR

Coal --> Grenade
Iron --> Grenade

subgraph Liquid
  SulAcid
  HeavyOil
  LightOil
  Petroleum
end

Coal ---> HeavyOil
SulAcid --> HeavyOil
Kalcite --> HeavyOil
HeavyOil --> LightOil
Water --> LightOil
LightOil --> Petroleum
Water --> Petroleum

Petroleum --> Sulfur
Water --> Sulfur
Coal --> Explosive
Sulfur --> Explosive
Water --> Explosive

Steel --> Barrel
Explosive --> CliffExp
Barrel --> CliffExp
Kalcite --> CliffExp
Grenade --> CliffExp
```
