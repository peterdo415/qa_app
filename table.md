テーブル

| users |  |  |  |  |
| --- | --- | --- | --- | --- |
| id | integer |  |  |  |
| name | string |  |  |  |
| email | string |  |  |  |
| password_digest | string |  |  |  |
| adimin | boolean |  |  |  |
| created_at | datetime(6) |  | questions |  |
| updated_at | datetime(6) | ← user_id:id | id | inetger |
|  |  |  | title | string |
| ↑user_id:id |  |  | content | text |
|  |  |  | solved | boolean |
| answers |  |  | user_id | integer |
| id | integer | question_id:id → | created_at | datetime(6) |
| content | text |  | updated_at | datetime(6) |
| user_id | integer |  |  |  |
| question_id | integer |  |  |  |
| created_at | datetime(6) |  |  |  |
| updated_at | datetime(6) |  |  |  |