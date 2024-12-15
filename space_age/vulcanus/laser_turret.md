```mermaid
flowchart LR

subgraph green
IronPlate1
Cable
GreenChip
end

subgraph bat
IronPlate2
CopperPlate
SulAcid
Battery
end

MoltenIron-->IronPlate1
MoltenIron-->IronPlate2
MoltenCopper-->Cable
MoltenCopper-->CopperPlate

IronPlate1-->GreenChip
Cable-->GreenChip

MoltenIron-->Steel

IronPlate2-->Battery
CopperPlate-->Battery
SulAcid-->Battery

Steel-->LaserTurret
GreenChip-->LaserTurret
Battery-->LaserTurret
```
