Модуль для работы с СК-63 в proj4.js

### Пример
```ts
import proj4 from "proj4";
import { get } from "@geo-ts/sk63/";
console.log(proj4("WGS84", get("SK63I3_2").proj, [73.356141837, 54.985876655]).toString())
```