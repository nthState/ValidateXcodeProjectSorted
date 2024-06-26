# Validate Xcode Project file is sorted

This GitHub Action validates if an Xcode project file is sorted.

When working with other developers, you may find it easier to merge project files
that are sorted alphabetically.

## Inputs

### `project-path`

**Required** The path to the Xcode project file.

### `report-warnings-as-error`

**Optional** Report warnings as errors. Defaults to `false`.

## Example usage

```yaml
uses: nthState/ValidateXcodeProjectSorted
with:
  project-path: './ios/App.xcodeproj'
  report-warnings-as-error: true
```