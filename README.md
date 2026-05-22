 Trello API (`Trello Api.postman_collection.json`)

Tests against the [Trello REST API](https://developer.atlassian.com/cloud/trello/rest/) using API Key + Token authentication.

| # | Request | Method | Description |
|---|---------|--------|-------------|
| 1 | Create Board | POST | Create a new Trello board, save `boardId` to env |
| 2 | Get Board | GET | Fetch board by saved `boardId`, assert name matches |
| 3 | Update Board | PUT | Rename board, assert updated name in response |
| 4 | Delete Board | DELETE | Delete board, assert 200 |
| 5 | Create List | POST | Create a list inside the board, save `listId` |
| 6 | Get List | GET | Fetch list by saved `listId`, assert name matches |


---
