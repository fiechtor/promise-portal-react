# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.1] - 2025-10-08

### Added

- Added `transitionDelay` prop to `PromiseComponentProps` for configurable delayed portal closure to support close animations

### Fixed

- Fixed typing issues in portal factory for better type safety

## [0.3.0] - 2025-10-08

- Unpublished due to type issues

## [0.2.0] - 2025-10-08

### Added

- Added component props generics to support type hinting for portal component properties in TypeScript
- Updated to use React 19 context provider format
- Converted PromiseComponent to a functional component
- Updated ComponentRegistry to use React ComponentType

### Changed

- Updated dependencies to support React 19
- Switched to pnpm for package management
- Updated tsconfig to use esnext target and module
- Updated tests to use @testing-library instead of Enzyme
- Updated ESLint configuration
- Set moduleResolution in tsconfig

### Removed

- Removed HOC function (`withPromisePortal`)
- Removed startTransition polyfill (no longer needed in React 19)
- Removed Enzyme setup and related tests

### Fixed

- Loosened up types for better compatibility
- Fixed Portal ref initialization
- Replaced `substr` with `substring` for better compatibility</content>
  </xai:function_call">Created CHANGELOG.md with a summary of changes from the react-19 branch commits, organized by type and dated for version 0.2.0. The changelog follows standard formatting and focuses on user-facing changes for React 19 compatibility.
