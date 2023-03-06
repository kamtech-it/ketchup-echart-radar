# kup-chip

<!-- Auto Generated Below -->


## Properties

| Property      | Attribute      | Description                                                                                                                            | Type                                                                            | Default              |
| ------------- | -------------- | -------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------- | -------------------- |
| `customStyle` | `custom-style` | Custom style of the component.                                                                                                         | `string`                                                                        | `''`                 |
| `data`        | --             | List of elements.                                                                                                                      | `KupChipNode[]`                                                                 | `[]`                 |
| `displayId`   | `display-id`   | When enabled, the chip's text will display both the id and the value.                                                                  | `boolean`                                                                       | `false`              |
| `enableInput` | `enable-input` | When enabled, it's possible to add items to the chip's dataset through an input slot (kup-autocomplete, kup-combobox, kup-text-field). | `boolean`                                                                       | `false`              |
| `type`        | `type`         | The type of chip. Available types: input, filter, choice or empty for default.                                                         | `FChipType.CHOICE \| FChipType.FILTER \| FChipType.INPUT \| FChipType.STANDARD` | `FChipType.STANDARD` |


## Events

| Event                | Description                                                | Type                                     |
| -------------------- | ---------------------------------------------------------- | ---------------------------------------- |
| `kup-chip-blur`      | Triggered when a chip loses focus.                         | `CustomEvent<KupChipEventPayload>`       |
| `kup-chip-change`    | Triggered when the chip dataset changes.                   | `CustomEvent<KupChipChangeEventPayload>` |
| `kup-chip-click`     | Triggered when a chip is clicked.                          | `CustomEvent<KupChipEventPayload>`       |
| `kup-chip-focus`     | Triggered when a chip gets focused.                        | `CustomEvent<KupChipEventPayload>`       |
| `kup-chip-iconclick` | Triggered when the removal icon on input chips is clicked. | `CustomEvent<KupChipEventPayload>`       |


## Methods

### `getProps(descriptions?: boolean) => Promise<GenericObject>`

Used to retrieve component's props values.

#### Returns

Type: `Promise<GenericObject>`

List of props as object, each key will be a prop.

### `refresh() => Promise<void>`

This method is used to trigger a new render of the component.

#### Returns

Type: `Promise<void>`



### `setProps(props: GenericObject) => Promise<void>`

Sets the props to the component.

#### Returns

Type: `Promise<void>`




## CSS Custom Properties

| Name                           | Description                                                        |
| ------------------------------ | ------------------------------------------------------------------ |
| `--kup-chip-background-color`  | Sets background color of the component.                            |
| `--kup-chip-border-radius`     | Sets border radius of the chips.                                   |
| `--kup-chip-font-family`       | Sets font family of the chips.                                     |
| `--kup-chip-font-size`         | Sets font size of the chips.                                       |
| `--kup-chip-font-weight`       | Sets font weight of the chips.                                     |
| `--kup-chip-height`            | Sets height of the chips.                                          |
| `--kup-chip-indent-multiplier` | Sets the indentation multiplier for children chips.                |
| `--kup-chip-margin`            | Sets margin of the chips.                                          |
| `--kup-chip-padding`           | Sets padding of the chips.                                         |
| `--kup-chip-primary-color`     | Sets primary color of the component.                               |
| `--kup-chip-primary-color-rgb` | Sets primary color RGB values of the component (used for shaders). |
| `--kup-chip-text-color`        | Sets text color of the component.                                  |
| `--kup-chip-text-color-rgb`    | Sets text color RGB values of the component (used for shaders).    |


## Dependencies

### Used by

 - [kup-box](../kup-box)
 - [kup-card](../kup-card)
 - [kup-cell](../kup-cell)
 - [kup-data-table](../kup-data-table)
 - [kup-form](../kup-form)
 - [kup-image-list](../kup-image-list)
 - [kup-magic-box](../kup-magic-box)
 - [kup-tree](../kup-tree)

### Depends on

- [kup-card](../kup-card)
- [kup-badge](../kup-badge)

### Graph
```mermaid
graph TD;
  kup-chip --> kup-card
  kup-chip --> kup-badge
  kup-card --> kup-chip
  kup-autocomplete --> kup-list
  kup-autocomplete --> kup-card
  kup-list --> kup-list
  kup-list --> kup-radio
  kup-list --> kup-card
  kup-list --> kup-badge
  kup-radio --> kup-card
  kup-badge --> kup-badge
  kup-badge --> kup-card
  kup-text-field --> kup-card
  kup-color-picker --> kup-card
  kup-combobox --> kup-list
  kup-combobox --> kup-card
  kup-date-picker --> kup-card
  kup-rating --> kup-card
  kup-time-picker --> kup-card
  kup-time-picker --> kup-list
  kup-image --> kup-spinner
  kup-image --> kup-card
  kup-image --> kup-badge
  kup-spinner --> kup-card
  kup-button --> kup-card
  kup-button --> kup-badge
  kup-button-list --> kup-dropdown-button
  kup-button-list --> kup-card
  kup-button-list --> kup-badge
  kup-dropdown-button --> kup-list
  kup-dropdown-button --> kup-card
  kup-dropdown-button --> kup-badge
  kup-chart --> kup-card
  kup-gauge --> kup-card
  kup-progress-bar --> kup-card
  kup-form --> kup-chip
  kup-checkbox --> kup-card
  kup-data-table --> kup-chip
  kup-switch --> kup-card
  kup-tab-bar --> kup-card
  kup-tab-bar --> kup-badge
  kup-tree --> kup-chip
  kup-box --> kup-chip
  kup-cell --> kup-chip
  kup-image-list --> kup-chip
  kup-magic-box --> kup-chip
  style kup-chip fill:#f9f,stroke:#333,stroke-width:4px
```

----------------------------------------------

*Built with [StencilJS](https://stenciljs.com/)*
