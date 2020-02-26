[Polkadot JS API](../README.md) › [Globals](../globals.md) › ["primitive/Bool"](../modules/_primitive_bool_.md) › [Bool](_primitive_bool_.bool.md)

# Class: Bool

**`name`** Bool

**`description`** 
Representation for a boolean value in the system. It extends the base JS `Boolean` class

## Hierarchy

* [Boolean](_primitive_bool_.bool.md#static-boolean)

  ↳ **Bool**

## Implements

* [Codec](../interfaces/_types_codec_.codec.md)

## Index

### Constructors

* [constructor](_primitive_bool_.bool.md#constructor)

### Properties

* [registry](_primitive_bool_.bool.md#registry)
* [Boolean](_primitive_bool_.bool.md#static-boolean)

### Accessors

* [encodedLength](_primitive_bool_.bool.md#encodedlength)
* [hash](_primitive_bool_.bool.md#hash)
* [isEmpty](_primitive_bool_.bool.md#isempty)
* [isFalse](_primitive_bool_.bool.md#isfalse)
* [isTrue](_primitive_bool_.bool.md#istrue)

### Methods

* [eq](_primitive_bool_.bool.md#eq)
* [toHex](_primitive_bool_.bool.md#tohex)
* [toHuman](_primitive_bool_.bool.md#tohuman)
* [toJSON](_primitive_bool_.bool.md#tojson)
* [toRawType](_primitive_bool_.bool.md#torawtype)
* [toString](_primitive_bool_.bool.md#tostring)
* [toU8a](_primitive_bool_.bool.md#tou8a)

## Constructors

###  constructor

\+ **new Bool**(`registry`: [Registry](../interfaces/_types_registry_.registry.md), `value`: [Bool](_primitive_bool_.bool.md) | [Boolean](_primitive_bool_.bool.md#static-boolean) | [Uint8Array](_codec_raw_.raw.md#static-uint8array) | boolean | number): *[Bool](_primitive_bool_.bool.md)*

*Defined in [packages/types/src/primitive/Bool.ts:29](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L29)*

**Parameters:**

Name | Type | Default |
------ | ------ | ------ |
`registry` | [Registry](../interfaces/_types_registry_.registry.md) | - |
`value` | [Bool](_primitive_bool_.bool.md) &#124; [Boolean](_primitive_bool_.bool.md#static-boolean) &#124; [Uint8Array](_codec_raw_.raw.md#static-uint8array) &#124; boolean &#124; number | false |

**Returns:** *[Bool](_primitive_bool_.bool.md)*

## Properties

###  registry

• **registry**: *[Registry](../interfaces/_types_registry_.registry.md)*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md).[registry](../interfaces/_types_codec_.codec.md#registry)*

*Defined in [packages/types/src/primitive/Bool.ts:29](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L29)*

___

### `Static` Boolean

▪ **Boolean**: *BooleanConstructor*

Defined in node_modules/typescript/lib/lib.es5.d.ts:540

## Accessors

###  encodedLength

• **get encodedLength**(): *number*

*Defined in [packages/types/src/primitive/Bool.ts:41](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L41)*

**`description`** The length of the value when encoded as a Uint8Array

**Returns:** *number*

___

###  hash

• **get hash**(): *H256*

*Defined in [packages/types/src/primitive/Bool.ts:48](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L48)*

**`description`** returns a hash of the contents

**Returns:** *H256*

___

###  isEmpty

• **get isEmpty**(): *boolean*

*Defined in [packages/types/src/primitive/Bool.ts:55](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L55)*

**`description`** Checks if the value is an empty value (always false)

**Returns:** *boolean*

___

###  isFalse

• **get isFalse**(): *boolean*

*Defined in [packages/types/src/primitive/Bool.ts:62](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L62)*

**`description`** Checks if the value is an empty value (always false)

**Returns:** *boolean*

___

###  isTrue

• **get isTrue**(): *boolean*

*Defined in [packages/types/src/primitive/Bool.ts:69](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L69)*

**`description`** Checks if the value is an empty value (always false)

**Returns:** *boolean*

## Methods

###  eq

▸ **eq**(`other?`: any): *boolean*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Defined in [packages/types/src/primitive/Bool.ts:76](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L76)*

**`description`** Compares the value of the input to see if there is a match

**Parameters:**

Name | Type |
------ | ------ |
`other?` | any |

**Returns:** *boolean*

___

###  toHex

▸ **toHex**(): *string*

*Defined in [packages/types/src/primitive/Bool.ts:87](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L87)*

**`description`** Returns a hex string representation of the value

**Returns:** *string*

___

###  toHuman

▸ **toHuman**(): *boolean*

*Defined in [packages/types/src/primitive/Bool.ts:94](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L94)*

**`description`** Converts the Object to to a human-friendly JSON, with additional fields, expansion and formatting of information

**Returns:** *boolean*

___

###  toJSON

▸ **toJSON**(): *boolean*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Defined in [packages/types/src/primitive/Bool.ts:101](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L101)*

**`description`** Converts the Object to JSON, typically used for RPC transfers

**Returns:** *boolean*

___

###  toRawType

▸ **toRawType**(): *string*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Defined in [packages/types/src/primitive/Bool.ts:108](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L108)*

**`description`** Returns the base runtime type name for this instance

**Returns:** *string*

___

###  toString

▸ **toString**(): *string*

*Implementation of [Codec](../interfaces/_types_codec_.codec.md)*

*Defined in [packages/types/src/primitive/Bool.ts:115](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L115)*

**`description`** Returns the string representation of the value

**Returns:** *string*

___

###  toU8a

▸ **toU8a**(`isBare?`: undefined | false | true): *[Uint8Array](_codec_raw_.raw.md#static-uint8array)*

*Defined in [packages/types/src/primitive/Bool.ts:124](https://github.com/polkadot-js/api/blob/2d40d370f/packages/types/src/primitive/Bool.ts#L124)*

**`description`** Encodes the value as a Uint8Array as per the SCALE specifications

**Parameters:**

Name | Type | Description |
------ | ------ | ------ |
`isBare?` | undefined &#124; false &#124; true | true when the value has none of the type-specific prefixes (internal)  |

**Returns:** *[Uint8Array](_codec_raw_.raw.md#static-uint8array)*