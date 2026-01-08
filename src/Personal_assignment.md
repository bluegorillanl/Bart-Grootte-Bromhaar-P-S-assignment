# Sequence diagram

For the overal system there has been made a sequence diagram.
As seen in sequence diagram below there are 2 systems.
1 system called traveling and 1 system called Coffee.

The sequence diagram:
```plantuml
@startuml
title sequence diagram
actor Person
participant "Travel" as Travel
participant "Coffee Pickup" as Coffee
Person -> Travel: Start travel to school
== Travel states (Program 1) ==
Travel -> Travel: State 1: Bike to station
Travel -> Travel: State 2: Getting in train
Travel -> Travel: State 3: Arrive at station Enschede
Travel -> Travel: State 4: Travel to Coffeestore
== Getting Coffee ==
Travel -> Coffee: Enable coffee pickup
Person -> Coffee: Pick up coffee
Coffee --> Travel: Coffee picked up (OK)
== Continue travel ==
Travel -> Travel: State 5: Travel to school
Travel -> Travel: State 6: Arrive at school
Travel --> Person: Travel completed
@enduml
```