---
title: Callbacks
---

### ox:getStatus

```lua
lib.callback.await('ox:getStatus', delay, targetId, statusName)
```

- delay: `number`
- targetId: `number`
  - The server id for the player to get statuses for.
- statusName?: `string`
  - The name of the status (i.e. hunger). Can be omitted to return all statuses.

### ox:getLicense

```lua
lib.callback.await('ox:getLicense', delay, licenseName, targetId)
```

- delay: `number`
- licenseName: `string`
  - The name of the license to get data for. Can be omitted to return all licenses.
- targetId?: `number`
  - The server id to get license data for, defaulting to the current player.
