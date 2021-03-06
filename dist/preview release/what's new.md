# 5.0.0

## Major updates

## Updates

- Added a `FocusableButton` gui control to simplify creating menus with keyboard navigation ([Flux159](https://github.com/Flux159))
- Added `focus()` and `blur()` functions for controls that implement `IFocusableControl` ([Flux159](https://github.com/Flux159))

### General

- Added static CenterToRef for vectors 2/3/4  ([aWeirdo](https://github.com/aWeirdo))

### Loaders

- Added support for EXT_meshopt_compression for glTF loader. ([zeux](https://github.com/zeux))

### Materials

- Added an `OcclusionMaterial` to simplify depth-only rendering of geometry ([rgerd](https://github.com/rgerd))

## Bugs

- Fix issue with the Promise polyfill where a return value was expected from resolve() ([Deltakosh](https://github.com/deltakosh))
- Fix an issue with keyboard control (re)attachment. ([#9411](https://github.com/BabylonJS/Babylon.js/issues/9411)) ([RaananW](https://github.com/RaananW))

## Breaking changes

- Use both `mesh.visibility` and `material.alpha` values to compute the global alpha value used by the soft transparent shadow rendering code. Formerly was only using `mesh.visibility` ([Popov72](https://github.com/Popov72))
