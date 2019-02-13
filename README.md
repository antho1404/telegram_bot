# telegram_bot
Mesg service for running telegram bot


```bash
mesg-core service deploy https://github.com/joveeee/telegram_bot
```

## Tasks

### Send message

Task key: **sendMessage**



#### Inputs

| **key** | **type** | **description** |
| --- | --- | --- |
| **chatId** | `Number` | Telegram user chat id 
| **text** | `String` | Message text |


#### Outputs

##### error

Output key: **error**

Return a `error` with the error

| **key** | **type** | **description** |
| --- | --- | --- |
| **error** | `String` |  |

##### success

Output key: **success**

| **key** | **type** | **description** |
| --- | --- | --- |
| **message** | `String` |  | |




