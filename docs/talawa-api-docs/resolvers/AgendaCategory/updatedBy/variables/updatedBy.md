[**talawa-api**](../../../../README.md) • **Docs**

***

[talawa-api](../../../../modules.md) / [resolvers/AgendaCategory/updatedBy](../README.md) / updatedBy

# Variable: updatedBy

\> `const` **updatedBy**: [`AgendaCategoryResolvers`](../../../../types/generatedGraphQLTypes/type-aliases/AgendaCategoryResolvers.md)\[`"updatedBy"`\]

Resolver function for the `updatedBy` field of an `AgendaCategory`.

This function retrieves the user who last updated a specific agenda category.

## Param

The parent object representing the agenda category. It contains information about the agenda category, including the ID of the user who last updated it.

## Returns

A promise that resolves to the user document found in the database. This document represents the user who last updated the agenda category.

## See

 - User - The User model used to interact with the users collection in the database.
 - AgendaCategoryResolvers - The type definition for the resolvers of the AgendaCategory fields.

```typescript
return User.findOne(\{ _id: parent.updatedBy \}).lean();
```

## Defined in

[src/resolvers/AgendaCategory/updatedBy.ts:19](https://github.com/PalisadoesFoundation/talawa-api/blob/f9e8275b1ddff2d3edcec79ee3b37c07998f6cc3/src/resolvers/AgendaCategory/updatedBy.ts#L19)
