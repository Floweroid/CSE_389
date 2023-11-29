# 1.1 api.md

| URL            |      [`/app/`](../api_doc_tem.md)      |
| :------------- | :------------------------------------: |
| Request Method |     `GET` `Post` `DELETE` `OPTION`     |
| Usage          | Descritpion about the usage of the api |

## Request

### Request Args:

| Arg  |    Type    | Description | Comment | Requirement |
| :--- | :--------: | ----------- | ------- | :---------: |
| data | dictionary |             |         | `O` or `X`  |
|      |            |             |         | `O` or `X`  |

```json
{
    data:{
        ...
    }
}
```

### Data:

| Arg | Type | Description | Comment | Requirement |
| :-- | :--: | ----------- | ------- | :---------: |
|     |      |             |         | `O` or `X`  |
|     |      |             |         | `O` or `X`  |

```json
{
    data:{
        ...
    }
}
```

### Request Args Obeject 1:

| Arg | Type | Description | Comment | Requirement |
| :-- | :--: | ----------- | ------- | :---------: |
|     |      |             |         | `O` or `X`  |
|     |      |             |         | `O` or `X`  |

## Response

### Request Args:

| Arg     |    Type    | Description | Comment | Requirement |
| :------ | :--------: | ----------- | ------- | :---------: |
| status  |    int     |             |         | `O` or `X`  |
| message |   string   |             |         | `O` or `X`  |
| data    | dictionary |             |         | `O` or `X`  |

```json
{
    status: 200,
    message: success,
    data:{
        ...
    }
}
```

### Data:

| Arg | Type | Description | Comment | Requirement |
| :-- | :--: | ----------- | ------- | :---------: |
|     |      |             |         | `O` or `X`  |
|     |      |             |         | `O` or `X`  |

```json
{
    data:{
        ...
    }
}
```

### Sucess Example


```json
{
    status: 200,
    message: success,
    data:{
        ...
    }
}
```

### Failed Example

```json
{
    status: 500,
    message: request failed,
    data:{
        ...
    }
}
```