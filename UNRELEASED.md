# Unreleased changes

### Breaking changes

### Enhancements

- Added `hideTags` prop to `Filters` ([#2573](https://github.com/Shopify/polaris-react/pull/2573))
- Added `searchResultsOverlayVisible` prop to `TopBar` which adds a translucent background to the search dismissal overlay when results are displayed ([#2440](https://github.com/Shopify/polaris-react/pull/2440))

### Bug fixes

- Fixed issue with `Filters` component displaying an undesired margin top and bottom on the button element on Safari ([#2292](https://github.com/Shopify/polaris-react/pull/2292))
- Doesn't render `MenuActions` if no actions are passed to an `actionGroups` item inside `Page` ([#2266](https://github.com/Shopify/polaris-react/pull/2266))
- Fixed `PositionedOverlay` incorrectly calculating `Topbar.UserMenu` `Popover` width ([#1692](https://github.com/Shopify/polaris-react/pull/1692))
- Fixed `recolor-icon` Sass mixin to properly scope `$secondary-color` to the child `svg` ([#2298](https://github.com/Shopify/polaris-react/pull/2298))
- Fixed a regression with the positioning of the `Popover` component ([#2305](https://github.com/Shopify/polaris-react/pull/2305))
- Fixed Stack Item proportion when shrinking ([#2319](https://github.com/Shopify/polaris-react/pull/2319))
- Fixed `RangeSlider` focus state style issues ([#1926](https://github.com/Shopify/polaris-react/pull/1926))
- Search dismissal overlay now covers the entire screen ([#2440](https://github.com/Shopify/polaris-react/pull/2440))
- Search results component will no longer unmount when hidden ([#2440](https://github.com/Shopify/polaris-react/pull/2440))
- Search results will now match the width of the search field ([#2440](https://github.com/Shopify/polaris-react/pull/2440))

### Documentation

### Development workflow

### Dependency upgrades

### Code quality

- Converted `BulkActionButton` into a functional component ([#2542](https://github.com/Shopify/polaris-react/pull/2542))
- Converted `Focus` into a functional component ([#2540](https://github.com/Shopify/polaris-react/pull/2540))
- Converted `Tooltip` into a functional component ([#2543](https://github.com/Shopify/polaris-react/pull/2543))

### Deprecations
