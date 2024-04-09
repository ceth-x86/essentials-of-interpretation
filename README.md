
```shell
npm install -g syntax-cli
```

```shell
syntax-cli --grammar parser/eva-grammar.bnf --mode LALR1 --parse '42' --tokenize
syntax-cli --grammar parser/eva-grammar.bnf --mode LALR1 --parse '(+ 5 foo)' --tokenize

syntax-cli --grammar parser/eva-grammar.bnf --mode LALR1 --output parser/evaParser.js
```