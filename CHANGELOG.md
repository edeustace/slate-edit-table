# Change Log
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this project adheres to [Semantic Versioning](http://semver.org/).

## [Unreleased]

### Changed
- `removeColumn` clears the column instead, if it is the last remaining column
- `removeRow` clears the row instead, if it is the last remaining row

### Fixed
- Undo of `insertColumn` when cursor is in inserted column

## [0.5.1] - 2016-09-15
### Changed
- `insertTable` does not grab text from current block anymore, and simply insert an empty table.

### Fixed
- Up/Down arrows behavior inside tables

## [0.5.0] - 2016-09-15
### Added
- `TablePosition.is{First|Last}{Row|Column|Cell}` methods

### Changed
- **BREAKING** Now uses `slate^0.14.x`
- Split transform `moveSelection` into `moveSelection` and `moveSelectionBy`

## [0.4.0] - 2016-09-06
### Added
- Schema normalization rules

  [Unreleased]: https://github.com/GitbookIO/slate-edit-table/compare/0.5.1...HEAD
  [0.5.1]: https://github.com/GitbookIO/slate-edit-table/compare/0.5.0...0.5.1
  [0.5.0]: https://github.com/GitbookIO/slate-edit-table/compare/0.4.0...0.5.0
  [0.4.0]: https://github.com/GitbookIO/slate-edit-table/compare/0.3.0...0.4.0