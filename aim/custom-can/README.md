# Custom CAN
## HALTECH_ECU_Broadcast.xc1
While Aim includes a Haltech protocol, it isn't complete, and can't be modified.
This contains whatever fields I felt were necessary for my car from the [Haltech ECU CAN Broadcast Protocol](https://support.haltech.com/portal/en/kb/articles/haltech-can-ecu-broadcast-protocol) definition.
Feel free to add your own, and please let me know if I messed any of them up! PRs are always welcome.

## TEVES_MK60E1_Race.xc1
A custom implementation for a MK60E1 that's been reflashed with a custom Continental "race tune"... or something.
The flashed ABS modules always broadcast CAN data, and don't require a wake-up message.
