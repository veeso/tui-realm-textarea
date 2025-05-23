# Changelog

- [Changelog](#changelog)
  - [2.1.0](#210)
  - [2.0.0](#200)
  - [1.1.2](#112)
  - [1.1.1](#111)
  - [1.1.0](#110)
  - [1.0.0](#100)

---

## 2.1.0

Relased on 23/03/2025

- `ratatui` `0.29`
- `tui-textarea` updated to `^0.7`

## 2.0.0

Released on 13/10/2024

- [Single line mode](https://github.com/veeso/tui-realm-textarea/pull/6)
- tuirealm 2.0

## 1.1.2

Released on 29/08/2023

Thanks to [@erak](https://github.com/erak)

- Added support for multiline paste command. [#5](https://github.com/veeso/tui-realm-textarea/pull/5)
- Added optional border. [#4](https://github.com/veeso/tui-realm-textarea/pull/4)
- Don't show cursor if not active. [#3](https://github.com/veeso/tui-realm-textarea/pull/3)

## 1.1.1

Released on 17/10/2022

- Updated `tui-textarea` to `^0.1.6`

## 1.1.0

Released on 02/08/2022

- Added `search` feature which enable text search
  - new commands:
    - `TEXTAREA_CMD_SEARCH_FORWARD`: go to next element in search
    - `TEXTAREA_CMD_SEARCH_BACK`: go to previous element in search
  - new props:
    - `TEXTAREA_SEARCH_PATTERN`: set search pattern
    - `TEXTAREA_SEARCH_STYLE`: set found elements style
- hard tab support via `TEXTAREA_HARD_TAB` property.

## 1.0.0

Released on 23/06/2022

- First release
