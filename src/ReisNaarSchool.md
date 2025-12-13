# Program_1: Travel to school

This program is about how to travel from home to school.
But no day can start without a good morning coffee!
So before this program can finish, first it needs something from "program 2". COFFEE!!

```plantuml
@startuml
title flowchart - Reis naar Enschede

Start -> Fiets_naar_station_Almelo
Fiets_naar_station_Almelo -> Op_station_Almelo 
Op_station_Almelo -> Trein_naar_Enschede
Trein_naar_Enschede -> Op_station_Enschede
Op_station_Enschede -> Loop_naar_school 
Loop_naar_school -> Op_school_met_koffie
@enduml
```