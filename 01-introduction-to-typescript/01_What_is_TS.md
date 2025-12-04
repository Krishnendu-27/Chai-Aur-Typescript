how we write function in js like this 
```javascript
function greet(name){
return "hallo" + name;
}
```
but its can take input any data type but we want string  to remove this type copnfution TS neeeded 
in js just one thing change its have types 
it help to remove bug also 
in js it give freedom to use types 
loose Docs -> it give docs of our code but due to js is non - data type language it give not the docs  correctly 
Developer tool and AI help with ts becuse it have types 

TS is alwys addon in JS it not work on his own TS is not run  but follow this process 
- it chack types 
- code consistency
TS -> process -> js 


```typescript
function greet(name:string):string{
return `helo ${name}`;
}
console.log(greet('hitesh'))
console.log(greet('42'))
```
