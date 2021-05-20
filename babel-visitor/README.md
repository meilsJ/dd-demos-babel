## DEMO —— babel 访问者

### 功能描述：

打印出 Visitor 访问者对象的遍历过程。

### 执行

```sh
node ./babel.js
```

### 执行结果

```js
enter Program(program)
enter FunctionDeclaration(0)
enter Identifier(id)
  exit Identifier(id)
enter Identifier(0)
  exit Identifier(0)
enter BlockStatement(body)
enter ExpressionStatement(0)
enter CallExpression(expression)
enter MemberExpression(callee)
enter Identifier(object)
  exit Identifier(object)
enter Identifier(property)
  exit Identifier(property)
  exit MemberExpression(callee)
enter BinaryExpression(0)
enter BinaryExpression(left)
enter StringLiteral(left)
  exit StringLiteral(left)
enter Identifier(right)
  exit Identifier(right)
  exit BinaryExpression(left)
enter StringLiteral(right)
  exit StringLiteral(right)
  exit BinaryExpression(0)
  exit CallExpression(expression)
  exit ExpressionStatement(0)
  exit BlockStatement(body)
  exit FunctionDeclaration(0)
  exit Program(program)
```
