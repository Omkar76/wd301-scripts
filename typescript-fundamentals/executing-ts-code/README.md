# Text

In this level, we will learn about executing and running TypeScript code. If you're new to TypeScript, you might be wondering how to take the code that you've written and actually run it in a web browser or other environment. Let us go over the steps you need to follow to do just that.

Before we begin, it's important to note that TypeScript code cannot be directly run in a web browser or other environment. This is because TypeScript is a compiled language, which means that it needs to be transformed into plain JavaScript before it can be executed. However, the TypeScript compiler makes this process easy and straightforward.

Here are the steps you'll need to follow to execute and run your TypeScript code: 

- Install the TypeScript compiler: First, you'll need to install the TypeScript compiler on your machine. You can do this by running the following command:

```
npm install -g typescript
```

- Compile your TypeScript code: Once you have the TypeScript compiler installed, you can use it to compile your TypeScript code into JavaScript. To do this, navigate to the directory containing your TypeScript files and run the following command:
```
tsc index.ts
```

- This will compile your `index.ts` file into a corresponding `index.js` file. You can also compile multiple TypeScript files at once by specifying them as additional arguments, like this:

```
tsc index.ts main.ts
```

- Run the generated JavaScript code: Once your TypeScript code has been compiled into JavaScript, you can run it just like you would any other JavaScript code. If you're running it in a web browser, you can do this by including the generated `.js` file in your HTML file like so:
```html
<script src="index.js"></script>
```

- Alternatively, you can run the generated JavaScript code using `Node.js` by running the following command:

```
node index.js
```

You should now be able to execute and run your TypeScript code in your chosen environment.

Let us learn more about Typescript in future lessons. See you at the next one.