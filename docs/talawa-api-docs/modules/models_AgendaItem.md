[talawa-api](../README.md) / [Exports](../modules.md) / models/AgendaItem

# Module: models/AgendaItem

## Table of contents

### Enumerations

- [ItemType](../enums/models_AgendaItem.ItemType.md)

### Interfaces

- [InterfaceAgendaItem](../interfaces/models_AgendaItem.InterfaceAgendaItem.md)

### Variables

- [AgendaItemModel](models_AgendaItem.md#agendaitemmodel)
- [AgendaItemSchema](models_AgendaItem.md#agendaitemschema)

## Variables

### AgendaItemModel

• `Const` **AgendaItemModel**: `Model`\<[`InterfaceAgendaItem`](../interfaces/models_AgendaItem.InterfaceAgendaItem.md), \{\}, \{\}, \{\}, `Document`\<`unknown`, \{\}, [`InterfaceAgendaItem`](../interfaces/models_AgendaItem.InterfaceAgendaItem.md)\> & [`InterfaceAgendaItem`](../interfaces/models_AgendaItem.InterfaceAgendaItem.md) & `Required`\<\{ `_id`: `ObjectId`  \}\>, `any`\>

#### Defined in

[src/models/AgendaItem.ts:133](https://github.com/PalisadoesFoundation/talawa-api/blob/9fa6a1c/src/models/AgendaItem.ts#L133)

___

### AgendaItemSchema

• `Const` **AgendaItemSchema**: `Schema`\<`any`, `Model`\<`any`, `any`, `any`, `any`, `any`, `any`\>, \{\}, \{\}, \{\}, \{\}, `DefaultSchemaOptions`, \{ `attachments`: `string`[] ; `categories`: `ObjectId`[] ; `createdAt`: `undefined` \| ``null`` \| `Date` ; `createdBy`: `undefined` \| ``null`` \| `ObjectId` ; `description`: `undefined` \| ``null`` \| `string` ; `duration`: `string` ; `itemType`: `undefined` \| ``null`` \| [`Regular`](../enums/models_AgendaItem.ItemType.md#regular) \| [`Note`](../enums/models_AgendaItem.ItemType.md#note) ; `notes`: `ObjectId`[] ; `organization`: `undefined` \| ``null`` \| `ObjectId` ; `relatedEventId`: `undefined` \| ``null`` \| `ObjectId` ; `sequence`: `undefined` \| ``null`` \| `number` ; `title`: `string` ; `updatedAt`: `undefined` \| ``null`` \| `Date` ; `updatedBy`: `undefined` \| ``null`` \| `ObjectId` ; `urls`: `string`[] ; `users`: `ObjectId`[]  \}, `Document`\<`unknown`, \{\}, `FlatRecord`\<\{ `attachments`: `string`[] ; `categories`: `ObjectId`[] ; `createdAt`: `undefined` \| ``null`` \| `Date` ; `createdBy`: `undefined` \| ``null`` \| `ObjectId` ; `description`: `undefined` \| ``null`` \| `string` ; `duration`: `string` ; `itemType`: `undefined` \| ``null`` \| [`Regular`](../enums/models_AgendaItem.ItemType.md#regular) \| [`Note`](../enums/models_AgendaItem.ItemType.md#note) ; `notes`: `ObjectId`[] ; `organization`: `undefined` \| ``null`` \| `ObjectId` ; `relatedEventId`: `undefined` \| ``null`` \| `ObjectId` ; `sequence`: `undefined` \| ``null`` \| `number` ; `title`: `string` ; `updatedAt`: `undefined` \| ``null`` \| `Date` ; `updatedBy`: `undefined` \| ``null`` \| `ObjectId` ; `urls`: `string`[] ; `users`: `ObjectId`[]  \}\>\> & `FlatRecord`\<\{ `attachments`: `string`[] ; `categories`: `ObjectId`[] ; `createdAt`: `undefined` \| ``null`` \| `Date` ; `createdBy`: `undefined` \| ``null`` \| `ObjectId` ; `description`: `undefined` \| ``null`` \| `string` ; `duration`: `string` ; `itemType`: `undefined` \| ``null`` \| [`Regular`](../enums/models_AgendaItem.ItemType.md#regular) \| [`Note`](../enums/models_AgendaItem.ItemType.md#note) ; `notes`: `ObjectId`[] ; `organization`: `undefined` \| ``null`` \| `ObjectId` ; `relatedEventId`: `undefined` \| ``null`` \| `ObjectId` ; `sequence`: `undefined` \| ``null`` \| `number` ; `title`: `string` ; `updatedAt`: `undefined` \| ``null`` \| `Date` ; `updatedBy`: `undefined` \| ``null`` \| `ObjectId` ; `urls`: `string`[] ; `users`: `ObjectId`[]  \}\> & \{ `_id`: `ObjectId`  \}\>

This is the Mongoose schema for an agenda item.

**`Param`**

Title of the agenda item.

**`Param`**

Optional description of the agenda item.

**`Param`**

Reference to the event associated with the agenda item.

**`Param`**

Duration of the agenda item.

**`Param`**

Optional array of attachment URLs.

**`Param`**

Reference to the user who created the agenda item.

**`Param`**

Reference to the user who last updated the agenda item.

**`Param`**

Optional users array indicating key note users for the agenda item.

**`Param`**

Optional user associated with the agenda item.

**`Param`**

Optional array of agenda categories associated with the agenda item.

**`Param`**

Sequence number of the agenda item.

**`Param`**

Type of the agenda item (Regular or Note).

**`Param`**

Date when the agenda item was created.

**`Param`**

Date when the agenda item was last updated.

**`Param`**

Indicates whether the agenda item is a note.

**`Param`**

Reference to the organization associated with the agenda item.

**`Param`**

Reference to the notes associated with the agenda item.

#### Defined in

[src/models/AgendaItem.ts:60](https://github.com/PalisadoesFoundation/talawa-api/blob/9fa6a1c/src/models/AgendaItem.ts#L60)
