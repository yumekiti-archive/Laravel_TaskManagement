## 概要
- １号館
  - １階
    - やること（順番）（重要度）(複雑さ)
  - ２階
    - やること（順番）（重要度）(複雑さ)

## テーブル

### tasks（やること）
| name | type |
|-|-|
| id | bigIncrements |
| title | string |
| detail | string |
| complexity | biginteger |
| importance | biginteger |

### management（現状態）
| name | type |
|-|-|
| task_id | bigIncrements |
| limit | time |
| status | boolean |
| building | integer |
| floor | integer |
| timestamps | timestamps |

### templates（テンプレート）
| name | type |
|-|-|
| id | bigIncrements |
| title | string |
| body | json |
| timestamps | timestamps |
