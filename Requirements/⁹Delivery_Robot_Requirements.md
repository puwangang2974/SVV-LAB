| Req. ID | Requirement Description | Priority |
|---|---|---|
| R1 | The system shall stay in IDLE state until a delivery request is received. | High |
| R2 | On receiving a delivery request, the system shall transition from IDLE to NAVIGATING. | High |
| R3 | While NAVIGATING, the system shall continuously scan for obstacles. | High |
| R4 | If an obstacle is detected while NAVIGATING, the system shall transition to AVOIDING_OBSTACLE. | High |
| R5 | Once the obstacle is cleared, the system shall transition back from AVOIDING_OBSTACLE to NAVIGATING. | High |
| R6 | When the destination is reached while NAVIGATING, the system shall transition to DELIVERING. | High |
| R7 | After a successful delivery, the system shall transition from DELIVERING to RETURNING. | Medium |
| R8 | If battery becomes critically low while NAVIGATING, the system shall abort the delivery and transition to RETURNING. | High |
| R9 | When the warehouse is reached while RETURNING, the system shall transition back to IDLE. | Medium |
| R10 | The system shall never transition directly into DELIVERING except from NAVIGATING (not from IDLE or AVOIDING_OBSTACLE). | High |
