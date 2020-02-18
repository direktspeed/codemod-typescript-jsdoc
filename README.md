# codemod-typescript-jsdoc
A CodeMod that takes a typescript project creates the resulting d.ts and creates ESNext + JSDOC Comments.

## Why
More and More and even More Young unexpirenced people choose typescript as firstclass for the project they are doing-
They are not aware of the new Module System for JS that got introduced with ESNext so they think compiling is always needed.

This leads to the conclusion that its good to go for TypeScript as you need to compile anyway but thats not true anymore

## Today 2020+
You can write valid ESNext code into a .js file it will later be the .mjs extension but as your coming from typescript and
typescript is slow in changing that behavior your doomed to use .js. But the Good news is you can Still use Typescript
you will simply write your interfaces as JSDOC into your ESNext .js files and you will simply edit the package.json next to the
project to include type: module thats it additional you will turn on the typescript checkJs: true option and your done.

## What did you win?
You Can directly debug and execute your real code without delay or additional overhead. Also your Harddrive will thank you a lot because you don't write always thousend of files if you edit 1 file.

- Faster Iterations
- You run untranspiled Code its the original Code
- Les fighting with bugs.
- your code base is highly adoptiv and reuseable 


