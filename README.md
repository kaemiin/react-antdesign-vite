# Test React + AntDesign + Vite

## Note

```
```

# REF

```
```

## Environment

```
node = v20.19.3
npm = 10.8.2
nrm = 2.0.1
```

## Run on Docker


```
docker run -it -d -v $(pwd):/workspace -p 3000:5173 --name react-antdesign-vite node:iron-bullseye bash

docker exec -it react-antdesign-vite bash

cd workspace
```

## Project Setup(開發人員)

Install nrm:

```
npm install -g nrm
```

Create a vite environment:

```
npm create vite@latest my-react-ant-design-app -- --template react
```

First Run:

```
cd workspace
npm install
npm run dev
```
