[talawa-api](../README.md) / [Exports](../modules.md) / resolvers/Mutation/createActionItem

# Module: resolvers/Mutation/createActionItem

## Table of contents

### Variables

- [createActionItem](resolvers_Mutation_createActionItem.md#createactionitem)

## Variables

### createActionItem

• `Const` **createActionItem**: [`MutationResolvers`](types_generatedGraphQLTypes.md#mutationresolvers)[``"createActionItem"``]

This function enables to create an action item.

**`Param`**

parent of current request

**`Param`**

payload provided with the request

**`Param`**

context of entire application

**`Remarks`**

The following checks are done:
1. If the user exists
2.If the user has appUserProfile
3. If the asignee exists
4. If the actionItemCategory exists
5. If the actionItemCategory is disabled
6. If the asignee is a member of the organization
7. If the user is a member of the organization
8. If the event exists (if action item related to an event)
9. If the user is authorized.

#### Defined in

[src/resolvers/Mutation/createActionItem.ts:50](https://github.com/PalisadoesFoundation/talawa-api/blob/9fa6a1c/src/resolvers/Mutation/createActionItem.ts#L50)
