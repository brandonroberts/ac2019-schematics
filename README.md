# Schematics

Install

``sh
yarn
```

Build library

```
yarn build my-lib
```

Build schematic

```
cd projects/my-lib
yarn build
```

Install schematic

```
cd ../../
npm link my-lib
```

Run schematic

```
ng g my-lib:my-service --name MyData
```
