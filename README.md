# React Three Fiber tutorial - Animate 3D Model[🔗](https://www.youtube.com/watch?v=mdj7Z3PCxRg&list=PLpepLKamtPjiUF6PvVUbIFhx9HaS0qJs_&index=2)

## Working with:

- [React Tree Fiber](https://r3f.netlify.app/docs)
- [Vite](https://vite.dev/)
- [Mantine](https://mantine.dev/)

## How to create project

First run `VS Code` as admin

```
npm create vite 
```
Set project name, select `React` and `JavaScpit` then open the folder

```
yarn add three @react-three/fiber @react-three/drei
yarn dev
```
Start the project, clean `App.jsx`, delete `index.css`, `App.css`

Get started with `Mantine`, install dependencies
```
yarn add @mantine/core @mantine/hooks
```

## Where to find a model
- [Unity Asset Store](https://assetstore.unity.com/)
- [Sketchfab](https://sketchfab.com/)

## Where to get animations
[Mixamo](https://www.mixamo.com/#/)

## How to animate the model
Transfer `.gltf` to `.jsx`
```
npx gltfjsx public/models/woman.gltf
```
