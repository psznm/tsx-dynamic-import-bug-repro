
./node_modules/.bin/tsx ./test.ts

Expected result:
```
test1-json
test1-ts
test2-json
test2-ts
```

Actual result:
```
test1-json
test1-json
test1-json
test1-json
```

./node_modules/.bin/tsx ./test2.ts

Expected result:
```
test1-json
test1-ts
test2-json
test2-ts
```

Actual result:
```
test1-json
test1-json
test2-json
test2-ts
```
