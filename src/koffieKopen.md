# Program_2: Buying coffee

The second program is about taking coffee from a coffestore.
The coffee is being prepared during the traveling.
When "Program 1" is at the 5th state, arrived in Enschede.

The coffee is picked up and only then the travel state can go on.

``` plantuml
@startuml

title Flowchart - Buy Coffee

[*] -> Start
Start -> Bestel_koffie
Bestel_koffie -> Wacht_tot_koffie_klaar
Wacht_tot_koffie_klaar -> Neem_koffie_aan
Neem_koffie_aan -> Loop_winkel_uit
Loop_winkel_uit -> [*]

@enduml

```
