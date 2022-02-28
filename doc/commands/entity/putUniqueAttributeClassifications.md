# pv entity putUniqueAttributeClassifications
[Command Reference](../../../README.md#command-reference) > [entity](./main.md) > putUniqueAttributeClassifications

## Description
Update classification on an entity identified by its type and unique attributes.

## Syntax
```
pv entity putUniqueAttributeClassifications --typeName=<val> --payloadFile=<val>
```

## Required Arguments
`--typeName` (string)  
The name of the type.

`--qualifiedName` (string)  
The qualified name of the entity.

`--payloadFile` (string)  
File path to a valid JSON document.

## Optional Arguments
*None*

## API Mapping
Catalog Data Plane > Entity > [Update Classifications By Unique Attribute](https://docs.microsoft.com/en-us/rest/api/purview/catalogdataplane/entity/update-classifications-by-unique-attribute)
```
PUT https://{accountName}.purview.azure.com/catalog/api/atlas/v2/entity/uniqueAttribute/type/{typeName}/classifications
```

## Examples
```powershell

```
<details><summary>Example payload: Create a ...</summary>
<p>

```json

```
</p>
</details>