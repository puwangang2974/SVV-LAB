## States

| State | Description |
|---|---|
| IDLE | Robot is idle, waiting for a delivery request. |
| NAVIGATING | Robot is moving toward the destination. |
| AVOIDING_OBSTACLE | Robot has paused normal navigation to avoid a detected obstacle. |
| DELIVERING | Robot is executing the delivery process at the destination. |
| RETURNING | Robot is heading back to the warehouse. |

## Events / Conditions

| Event | Description |
|---|---|
| Delivery Request Received | A new delivery request arrives while robot is idle. |
| Destination Reached | Robot arrives at the delivery destination. |
| Delivery Successful | Package has been delivered successfully. |
| Warehouse Reached | Robot arrives back at the warehouse. |
| Obstacle Detected | An obstacle is detected during navigation. |
| Obstacle Avoided | The detected obstacle has been successfully avoided. |
| Critical Battery | Battery level drops to a critically low level. |
