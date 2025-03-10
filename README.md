# WASM Postflop

Fork of https://github.com/b-inary/wasm-postflop

**WASM Postflop** is a free, open-source GTO solver for Texas hold'em poker that works on web browsers.
## Build

```sh
$ # prerequisites
$ rustup install nightly
$ rustup +nightly component add rust-src
$ rustup target add wasm32-unknown-unknown
$ cargo install wasm-pack
$ npm install

$ # build
$ npm run wasm
$ npm run build

$ # serve
$ npm run serve

$ # lint/format
$ npm run lint
$ npm run format
```

## License

Copyright (C) 2022 Wataru Inariba

This program is free software: you can redistribute it and/or modify it under the terms of the GNU Affero General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License along with this program.  If not, see <https://www.gnu.org/licenses/>.
