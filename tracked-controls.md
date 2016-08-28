---
title: tracked-controls
type: components
layout: docs
parent_section: components
---

The tracked-controls component interfaces with tracked controllers. 
Uses the OpenVR gamepad API to handled tracked controllers. Selects the appropriate controller and applies pose to the entity. 
It also observes buttons state and emits appropriate events.


## Example

```html
```

## Value

| Property             | Description                                        | Default Value        |
|----------------------|----------------------------------------------------|----------------------|
| controller           | Index of the controller in array from Gamepad API. | 0                    |
| id                   | Button colors when pressed and active.             | #22D1EE (light blue) |

## Events

| Event Name   | Description             |
| ----------   | -----------             |
| gripdown     | Grip button pressed.    |
| gripup       | Grip button released.   |
| menudown     | Menu button pressed.    |
| menuup       | Menu button released.   |
| systemdown   | System button pressed.  |
| systemup     | System button released. |
| trackpadup   | Trackpad pressed.       |
| trackpaddown | Trackpad released.      |
