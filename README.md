# Notes and example projects from TypeScript Course

#### Common commands

`tsc file.js` - complies the code to JS using the javascript compiler. Will raise error/ not compile if there is some issue in your code

#### General Notes

- Some reccomended extensions for VS code: ESLint, Path Intellisense, Pretier, Material Icon Theme
- Core Types (Important: core primative types in TypeScript are lowercase)
  - `number` - all numbers, no differentiation between integers and floats
  - `string` - all text values
  - `boolean`
  - `object` - Any JS object. More specific types are possible
  - `Array` - type can be flexible or strict
  - `Tuple` - Fixed-length array
  - `Enum` - Automatically enumerated global constant identifiers
  - `Any` - avoid when possible; basically takes away advantages of TS
- In funcion definitions, add `: type` after variable to set expected variable type
- Type Inference - typescript does its best to infer what type a variable should be
- TS types are check during compilation, JS types during runtime.
- When creating objects in TS, it is generally better to use type inference than explicity setting. However, if there is a scenario where type inference breaks down (ex. a tuple rather than array) you can explicitly define types.
- type aliases - allows you to define your own custom types

#### Project Descriptions

##### Getting Started

- first_project - very simple project showing esential benifits of js
- understanding_ts - working project used for introductory modules
