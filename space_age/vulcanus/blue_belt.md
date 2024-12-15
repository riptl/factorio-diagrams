```mermaid
flowchart LR

subgraph a1
Gear1
IronPlate
Gear2
YellowBelt
RedBelt
end

subgraph a2
SulAcid
Kalzit
Coal
HeavyOil
Lube
Gear3
end

Lava-->MoltenIron
Lava--->Stone
MoltenIron-->Gear1
MoltenIron-->IronPlate
MoltenIron-->Gear2
Gear1-->YellowBelt
IronPlate-->YellowBelt
YellowBelt-->RedBelt
Gear2-->RedBelt

SulAcid-->HeavyOil
Kalzit-->HeavyOil
Coal-->HeavyOil

HeavyOil-->Lube

MoltenIron-->Gear3
RedBelt-->BlueBelt
Gear3-->BlueBelt
Lube-->BlueBelt
```
