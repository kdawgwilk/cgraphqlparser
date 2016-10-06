# CGraphQLParser

C module for GraphQLParser

## Building

**To build on macOS:**

```sh
swift build -Xswiftc -I/usr/local/include/graphqlparser -Xlinker -L/usr/local/lib
```

- `-I` tells the compiler where to find the GraphQLParser header files:
```
GraphQLAstForEachConcreteType.h"
GraphQLAst.h"
GraphQLAstNode.h"
GraphQLAstToJSON.h"
GraphQLAstVisitor.h"
GraphQLParser.h"
```
- `-L` tells the linker where to find GraphQLParser library `libgraphqlparser`.

**To build on Linux:**

`swift build` should work normally.

## 💧 Community

Join the welcoming community of fellow Vapor developers in [slack](http://vapor.team).

## 🔧 Compatibility

This package has been tested on macOS and Ubuntu.