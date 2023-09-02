type IsEmptyType<T> = keyof T extends never ? true : false

Here the following cases are evaluated as below.
1. `any` is never empty object
2. `object` is never empty object
3. `Object` has constructor is never the empty object
