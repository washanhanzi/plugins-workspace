# Changelog

## \[2.0.0-alpha.7]

- [`ea8eadc`](https://github.com/tauri-apps/plugins-workspace/commit/ea8eadce85b2e3e8eb7eb1a779fc3aa6c1201fa3)([#865](https://github.com/tauri-apps/plugins-workspace/pull/865)) Fix incorrect `create` option default value for `writeFile` and `writeTextFile` which didn't match documentation.
- [`61edbbe`](https://github.com/tauri-apps/plugins-workspace/commit/61edbbec0acda4213ed8684f75a973e8be123a52)([#885](https://github.com/tauri-apps/plugins-workspace/pull/885)) Replace `notify-debouncer-mini` with `notify-debouncer-full`. [(plugins-workspace#885)](https://github.com/tauri-apps/plugins-workspace/pull/885)

## \[2.0.0-alpha.6]

- [`85f8419`](https://github.com/tauri-apps/plugins-workspace/commit/85f841968200316958d707db0c39bb115f762471)([#848](https://github.com/tauri-apps/plugins-workspace/pull/848)) Fix `DebouncedEvent` type to correctly represent the actual type.
- [`c601230`](https://github.com/tauri-apps/plugins-workspace/commit/c60123093ddf725af7228494182fed697ff8b021)([#847](https://github.com/tauri-apps/plugins-workspace/pull/847)) Add `createNew` option for `writeFile` and `writeTextFile` to create the file if doesn't exist and fail if it does.
- [`c601230`](https://github.com/tauri-apps/plugins-workspace/commit/c60123093ddf725af7228494182fed697ff8b021)([#847](https://github.com/tauri-apps/plugins-workspace/pull/847)) Truncate files when using `writeFile` and `writeTextFile` with `append: false`.
- [`2e2fc8d`](https://github.com/tauri-apps/plugins-workspace/commit/2e2fc8de69dd8d282b66ec81561d57d8af802dc5)([#857](https://github.com/tauri-apps/plugins-workspace/pull/857)) Fix `invalid args id for command unwatch` error when trying to unwatch a previously watched file or directory.
- [`c601230`](https://github.com/tauri-apps/plugins-workspace/commit/c60123093ddf725af7228494182fed697ff8b021)([#847](https://github.com/tauri-apps/plugins-workspace/pull/847)) Fix panic when using `writeFile` or `writeTextFile` without passing an option object.

## \[2.0.0-alpha.5]

- [`387c2f9`](https://github.com/tauri-apps/plugins-workspace/commit/387c2f9e0ce4c75c07ffa3fd76391a25b58f5daf)([#802](https://github.com/tauri-apps/plugins-workspace/pull/802)) Update to @tauri-apps/api v2.0.0-alpha.13.
- [`69a1fa0`](https://github.com/tauri-apps/plugins-workspace/commit/69a1fa099c3143b6e426492f1c9d9cfbe56d2209)([#751](https://github.com/tauri-apps/plugins-workspace/pull/751)) The `fs` plugin received a major overhaul to add new APIs and changed existing APIs to be closer to Node.js and Deno APIs.

## \[2.0.0-alpha.4]

- [`387c2f9`](https://github.com/tauri-apps/plugins-workspace/commit/387c2f9e0ce4c75c07ffa3fd76391a25b58f5daf)([#802](https://github.com/tauri-apps/plugins-workspace/pull/802)) Update to @tauri-apps/api v2.0.0-alpha.12.
- [`88d260d`](https://github.com/tauri-apps/plugins-workspace/commit/88d260d90130f9df4b9ce00c1ad1bf1e4b30b1c0)([#744](https://github.com/tauri-apps/plugins-workspace/pull/744)) Add second argument to `exists` function to specify base directory.

## \[2.0.0-alpha.3]

- [`e438e0a`](https://github.com/tauri-apps/plugins-workspace/commit/e438e0a62d4b430a5159f05f13ecd397dd891a0d)([#676](https://github.com/tauri-apps/plugins-workspace/pull/676)) Update to @tauri-apps/api v2.0.0-alpha.11.

## \[2.0.0-alpha.2]

- [`5c13736`](https://github.com/tauri-apps/plugins-workspace/commit/5c137365c60790e8d4037d449e8237aa3fffdab0)([#673](https://github.com/tauri-apps/plugins-workspace/pull/673)) Update to @tauri-apps/api v2.0.0-alpha.9.

## \[2.0.0-alpha.2]

- [`4e2cef9`](https://github.com/tauri-apps/plugins-workspace/commit/4e2cef9b702bbbb9cf4ee17de50791cb21f1b2a4)([#593](https://github.com/tauri-apps/plugins-workspace/pull/593)) Update to alpha.12.

## \[2.0.0-alpha.1]

- [`0bba693`](https://github.com/tauri-apps/plugins-workspace/commit/0bba6932c09da5267a9dbf75ba52252e39458420)([#454](https://github.com/tauri-apps/plugins-workspace/pull/454)) Fix `writeBinaryFile` crashing with `command 'write_binary_file' not found`
- [`d74fc0a`](https://github.com/tauri-apps/plugins-workspace/commit/d74fc0a097996e90a37be8f57d50b7d1f6ca616f)([#555](https://github.com/tauri-apps/plugins-workspace/pull/555)) Update to alpha.11.

## \[2.0.0-alpha.0]

- [`717ae67`](https://github.com/tauri-apps/plugins-workspace/commit/717ae670978feb4492fac1f295998b93f2b9347f)([#371](https://github.com/tauri-apps/plugins-workspace/pull/371)) First v2 alpha release!
  /pull/454)) Fix `writeBinaryFile` crashing with `command 'write_binary_file' not found`
- [`d74fc0a`](https://github.com/tauri-apps/plugins-workspace/commit/d74fc0a097996e90a37be8f57d50b7d1f6ca616f)([#555](https://github.com/tauri-apps/plugins-workspace/pull/555)) Update to alpha.11.

## \[2.0.0-alpha.0]

- [`717ae67`](https://github.com/tauri-apps/plugins-workspace/commit/717ae670978feb4492fac1f295998b93f2b9347f)([#371](https://github.com/tauri-apps/plugins-workspace/pull/371)) First v2 alpha release!
