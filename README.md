# Schematics

Install

```sh
yarn
```

Build library

```sh
yarn build my-lib
```

Build schematic

```sh
cd projects/my-lib
yarn build
```

Install schematic

```sh
cd ../../
npm link my-lib
```

Run schematic

```sh
ng g my-lib:my-service --name MyData
```
