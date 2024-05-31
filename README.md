# Validate Xcode Project file is sorted

This GitHub Action validates if an Xcode project file is sorted.

## Inputs

### `project-path`

**Required** The path to the Xcode project file.

## Example usage

```yaml
uses: nthState/ValidateXcodeProjectSorted
with:
  project-path: './ios/App.xcodeproj'
```