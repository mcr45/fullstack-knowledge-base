Typescript allows devs to check for bugs/errors that otherwise would go unnoticed.
You use typescript you need a compiler since some of the syntax is not js native.
npm i typescript allow to install typescript locally.
npx tsc --init create config file.
npx tsc file.ts compile file into a respective js file.


union type→let vaer:string|number
declare objects:  let person: {
  name: string;
  location: string;
  isProgrammer: boolean;
}
type aliases→type hotdogs=string|number, let vass:hotdogs




Generics: 
    Generics allow you to create a component that can work over a variety of types, rather than a single one, which helps to make the component more reusable