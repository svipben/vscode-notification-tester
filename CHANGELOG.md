## 2.1.0 (February 10, 2019)

- Replaced `TSLint` with `ESLint`.
- Removed `Prettier` config since it works nicely with `ESLint` so there's no reason of having it.
- Updated all dev dependencies.
- Refactored `CHANGELOG` and `README` to a new format.
- Replaced `Travis` with `Azure Pipelines`.
- Added `lint` script with `concurrent-run` dependency to concurrently lint with `eslint` and `tsc`.

## 2.0.4 (December 28, 2018)

- Created Prettier config.
- Updated license year.
- Added `max-line-length` rule to the TSLint.
- Some minor changes in `extension.ts`.
- Updated all dependencies to the latest version.

## 2.0.3 (December 16, 2018)

- Updated all dependencies to the latest version.

## 2.0.2 (October 28, 2018)

- Updated all dependencies to the latest version.
- Refactored code.

## 2.0.1 (July 8, 2018)

### Changed

- File name of `enum` and `class` to uppercase.
- ⬆️ dev dependencies.
- Surrounded tests with `try/catch` since they are `async` and added `Promise.all` for one of the test to improve performance.

## 2.0.0 (June 25, 2018)

### Added

- TravisCI with tests.

### Changed

- Totally rewritten to the TypeScript.

## 1.2.1 (May 5, 2018)

### Added

- Icon in `README.md`
- Visual Studio Marketplace badge in `README.md`

### Changed

- `images/notification.png` to `images/icon.png`
- Size and location of Notification Center image.
- ⬆️ `vscode` in `package.json` (devDependencies).

## 1.2.0 (April 2, 2018)

### Added

- `Show Progress Badge` and `Stop Progress Badge` commands to show/stop Progress Badge in Source Control. ([#2](https://github.com/svipben/vscode-notification-tester/issues/2))
- Link to the extension in `README.md`.

### Changed

- Notification Center image.

## 1.1.0 (March 9, 2018)

- Added dummy Yes and No buttons for all messages. ([#1](https://github.com/svipben/vscode-notification-tester/issues/1))
- Updated Notification Center image.
- Created `yarn.lock` file and added `vscode` dependency in `package.json` to enable autocomplete while developing extension.

## 1.0.0 (March 8, 2018)

- Initial release.
