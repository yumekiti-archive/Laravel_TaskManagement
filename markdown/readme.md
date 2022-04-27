## 概要
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
| building | bigIncrements |
| timestamps | timestamps |

### templates（テンプレート）
| name | type |
|-|-|
| id | bigIncrements |
| title | string |
| body | json |
| timestamps | timestamps |
