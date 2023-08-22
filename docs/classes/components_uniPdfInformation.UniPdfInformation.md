[printease](../README.md) / [Modules](../modules.md) / [components/uniPdfInformation](../modules/components_uniPdfInformation.md) / UniPdfInformation

# Class: UniPdfInformation

[components/uniPdfInformation](../modules/components_uniPdfInformation.md).UniPdfInformation

pdf information

## Implements

- [`PdfInformationInterface`](../interfaces/interface_pdfInformation.PdfInformationInterface.md)

## Table of contents

### Constructors

- [constructor](components_uniPdfInformation.UniPdfInformation.md#constructor)

### Properties

- [imageContent](components_uniPdfInformation.UniPdfInformation.md#imagecontent)
- [pageCount](components_uniPdfInformation.UniPdfInformation.md#pagecount)
- [pdfInstance](components_uniPdfInformation.UniPdfInformation.md#pdfinstance)
- [pdfjsLib](components_uniPdfInformation.UniPdfInformation.md#pdfjslib)
- [textContent](components_uniPdfInformation.UniPdfInformation.md#textcontent)

### Methods

- [getPdfImage](components_uniPdfInformation.UniPdfInformation.md#getpdfimage)
- [getPdfPageCount](components_uniPdfInformation.UniPdfInformation.md#getpdfpagecount)
- [getPdfText](components_uniPdfInformation.UniPdfInformation.md#getpdftext)
- [init](components_uniPdfInformation.UniPdfInformation.md#init)
- [loadPdfFile](components_uniPdfInformation.UniPdfInformation.md#loadpdffile)

## Constructors

### constructor

• **new UniPdfInformation**()

## Properties

### imageContent

• **imageContent**: {}[]

#### Implementation of

[PdfInformationInterface](../interfaces/interface_pdfInformation.PdfInformationInterface.md).[imageContent](../interfaces/interface_pdfInformation.PdfInformationInterface.md#imagecontent)

#### Defined in

components/uniPdfInformation/index.ts:6

___

### pageCount

• **pageCount**: `number` = `0`

#### Implementation of

[PdfInformationInterface](../interfaces/interface_pdfInformation.PdfInformationInterface.md).[pageCount](../interfaces/interface_pdfInformation.PdfInformationInterface.md#pagecount)

#### Defined in

components/uniPdfInformation/index.ts:4

___

### pdfInstance

• **pdfInstance**: `any`

#### Implementation of

[PdfInformationInterface](../interfaces/interface_pdfInformation.PdfInformationInterface.md).[pdfInstance](../interfaces/interface_pdfInformation.PdfInformationInterface.md#pdfinstance)

#### Defined in

components/uniPdfInformation/index.ts:8

___

### pdfjsLib

• **pdfjsLib**: `any`

#### Implementation of

[PdfInformationInterface](../interfaces/interface_pdfInformation.PdfInformationInterface.md).[pdfjsLib](../interfaces/interface_pdfInformation.PdfInformationInterface.md#pdfjslib)

#### Defined in

components/uniPdfInformation/index.ts:7

___

### textContent

• **textContent**: `object` = `{}`

#### Implementation of

[PdfInformationInterface](../interfaces/interface_pdfInformation.PdfInformationInterface.md).[textContent](../interfaces/interface_pdfInformation.PdfInformationInterface.md#textcontent)

#### Defined in

components/uniPdfInformation/index.ts:5

## Methods

### getPdfImage

▸ **getPdfImage**(`pageIndex`): `Promise`<`unknown`\>

get pdf image

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `pageIndex` | `number` | page number |

#### Returns

`Promise`<`unknown`\>

#### Implementation of

[PdfInformationInterface](../interfaces/interface_pdfInformation.PdfInformationInterface.md).[getPdfImage](../interfaces/interface_pdfInformation.PdfInformationInterface.md#getpdfimage)

#### Defined in

components/uniPdfInformation/index.ts:43

___

### getPdfPageCount

▸ **getPdfPageCount**(): `Promise`<`unknown`\>

get pdf page count

#### Returns

`Promise`<`unknown`\>

#### Implementation of

[PdfInformationInterface](../interfaces/interface_pdfInformation.PdfInformationInterface.md).[getPdfPageCount](../interfaces/interface_pdfInformation.PdfInformationInterface.md#getpdfpagecount)

#### Defined in

components/uniPdfInformation/index.ts:35

___

### getPdfText

▸ **getPdfText**(`page`): `Promise`<`unknown`\>

get pdf Text

#### Parameters

| Name | Type | Description |
| :------ | :------ | :------ |
| `page` | `number` | page number |

#### Returns

`Promise`<`unknown`\>

#### Implementation of

[PdfInformationInterface](../interfaces/interface_pdfInformation.PdfInformationInterface.md).[getPdfText](../interfaces/interface_pdfInformation.PdfInformationInterface.md#getpdftext)

#### Defined in

components/uniPdfInformation/index.ts:24

___

### init

▸ **init**(): `void`

init

#### Returns

`void`

#### Implementation of

[PdfInformationInterface](../interfaces/interface_pdfInformation.PdfInformationInterface.md).[init](../interfaces/interface_pdfInformation.PdfInformationInterface.md#init)

#### Defined in

components/uniPdfInformation/index.ts:9

___

### loadPdfFile

▸ **loadPdfFile**(`file`): `Promise`<`unknown`\>

load pdf file

#### Parameters

| Name | Type |
| :------ | :------ |
| `file` | `any` |

#### Returns

`Promise`<`unknown`\>

#### Implementation of

[PdfInformationInterface](../interfaces/interface_pdfInformation.PdfInformationInterface.md).[loadPdfFile](../interfaces/interface_pdfInformation.PdfInformationInterface.md#loadpdffile)

#### Defined in

components/uniPdfInformation/index.ts:15