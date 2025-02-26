# Missing

- [1. Property `Missing > id`](#id)
- [2. Property `Missing > label`](#label)
- [3. Property `Missing > description`](#description)
- [4. Property `Missing > code`](#code)

**Title:** Missing

|                           |                  |
| ------------------------- | ---------------- |
| **Type**                  | `object`         |
| **Required**              | No               |
| **Additional properties** | Any type allowed |

**Description:** Data structure to describe a missing status in the final data set.

| Property                       | Pattern | Type    | Deprecated | Definition | Title/Description                                                      |
| ------------------------------ | ------- | ------- | ---------- | ---------- | ---------------------------------------------------------------------- |
| + [id](#id )                   | No      | string  | No         | -          | Identifier for missing                                                 |
| + [label](#label )             | No      | string  | No         | -          | Short description. This text might be used as code label in data sets. |
| + [description](#description ) | No      | string  | No         | -          | Long description to explain meaning of that missing.                   |
| + [code](#code )               | No      | integer | No         | -          | Code used in data sets to represent this missing.                      |

## <a name="id"></a>1. Property `Missing > id`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** Identifier for missing

**Examples:**

```json
"mnr"
```

```json
"mir"
```

```json
"mb"
```

| Restrictions                      |                                                                                                    |
| --------------------------------- | -------------------------------------------------------------------------------------------------- |
| **Must match regular expression** | ```^[A-Za-z_]+$``` [Test](https://regex101.com/?regex=%5E%5BA-Za-z_%5D%2B%24&testString=%22mnr%22) |

## <a name="label"></a>2. Property `Missing > label`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** Short description. This text might be used as code label in data sets.

## <a name="description"></a>3. Property `Missing > description`

|              |          |
| ------------ | -------- |
| **Type**     | `string` |
| **Required** | Yes      |

**Description:** Long description to explain meaning of that missing.

## <a name="code"></a>4. Property `Missing > code`

|              |           |
| ------------ | --------- |
| **Type**     | `integer` |
| **Required** | Yes       |

**Description:** Code used in data sets to represent this missing.

**Examples:**

```json
-98
```

```json
-97
```

----------------------------------------------------------------------------------------------------------------------------
Generated using [json-schema-for-humans](https://github.com/coveooss/json-schema-for-humans) on 2025-02-26 at 09:27:22 +0000
