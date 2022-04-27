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

### buildings（何号館）
| name | type |
|-|-|
| id | bigIncrements |
| body | string |

### management（現状態）
| name | type |
|-|-|
| taskid | bigIncrements |
| limit | time |
| building_id | bigIncrements |

### templates（テンプレート）
| name | type |
|-|-|
| title | string |
| body | json |
