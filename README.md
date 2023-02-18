# node-gpt-repl

## About

`node-gpt(1)` is a Node.js REPL with built-in GPT3 completion and _auto-npm install_ on `require()` so you can experiment at the speed of thought!

## Installation

```
$ npm install -g node-gpt-repl
```

## Usage

Get an OpenAI API key and expose it in your environment:

```
export OPENAI_API_KEY=xxxxxxxxxxxx
```

In your terminal:

```
$ node-gpt
```

As you can see from the demo below the results are pretty crappy at the moment, but I think the idea is solid. Contributions welcome!

![Demo](demo.gif)