# Protoflux Render Engine Showcase

> A showcase of how the protoflux nodes are generated on this documentation.

## Normal

<!-- panels:start -->
<!-- div:left-panel -->
### Example

```md
<!-- ProtofluxNode:start -->
| Dynamic Impulse Trigger | Type          | Label            |
| ----------------------- | ------------- | ---------------- |
| input                   | Bool          | *                |
| output                  | String        | Next             |
| input                   | Bool          | Tag              |
| output                  | Int           | TriggeredCount   |
| input                   | String        | TargetHierarchy  |
| output                  | Double        | Some Output      |
| input                   | TriggerString | ExcludedDisabled |
| Async                   |               |                  |
<!-- ProtofluxNode:end -->
```
<!-- div:right-panel -->
### Output
<!-- ProtofluxNode:start -->
| Dynamic Impulse Trigger | Type          | Label            |
| ----------------------- | ------------- | ---------------- |
| input                   | Bool          | *                |
| output                  | String        | Next             |
| input                   | Bool          | Tag              |
| output                  | Int           | TriggeredCount   |
| input                   | String        | TargetHierarchy  |
| output                  | Double        | Some Output      |
| input                   | TriggerString | ExcludedDisabled |
| Async                   |               |                  |
<!-- ProtofluxNode:end -->
<!-- panels:end -->

## Operator

> [!Warning]
> This node-type is not yet implemented. The table will change before being implemented.

| Some function name |     |        |
| ------------------ | --- | ------ |
| String             | ==  | String |
| String             |     |        |
| Operator           |     |        |

## Input

> [!Warning]
> This node-type is not yet implemented. The table will change before being implemented.

### String

| Some function name |                 |        |
| ------------------ | --------------- | ------ |
| input              | Some field text | String |
| Core               |                 |        |

### URI

| Some function name |                 |     |
| ------------------ | --------------- | --- |
| input              | Some field text | URI |
| Core               |                 |     |

### Slot

| Some function name |                 |      |
| ------------------ | --------------- | ---- |
| input              | Some field text | Slot |
| Core               |                 |      |

### Bool

| Some function name |     |      |
| ------------------ | --- | ---- |
| input              |     | Bool |
| Core               |     |      |

### Button Call

| Some function name |      |         |
| ------------------ | ---- | ------- |
| input              | Call | Trigger |
| Core               |      |         |