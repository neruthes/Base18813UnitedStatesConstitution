# Base18813UnitedStatesConstitution

## Mechanism

The United States Constitution (USC) is used to encode arbitrary bytes (usually strings). Uppercase is `1` and lowercase is `0`.
Every byte is prepended with a `1` bit so it take 9 bits to represent 1 byte. If the prefix is bit `0`, the following byte is considered EOF. The EOF will not be included in the decoding output.

The USC has 21165 letters (`[A-Za-z]`). It can encode 18813 bits (2351 bytes). It can be generally enough for small data sets. If the input data is longer, repeat the USC multiple times to contain all data.

## Use

```
Base18813UnitedStatesConstitution.encodeString('This is the string you want to encode').
> 
```

## Web App

## Copyright

Copyright (c) 2020 Neruthes <[neruthes.xyz](https://neruthes.xyz)>.

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU Affero General Public License as published
by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU Affero General Public License for more details.

You should have received a copy of the GNU Affero General Public License
along with this program.  If not, see <https://www.gnu.org/licenses/>.
