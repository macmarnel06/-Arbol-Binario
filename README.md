# Binary Trees – Tree Traversals

Implement the four traversal methods in `src/main/java/TreeTraversals.java`:

| Method | Visit order |
|---|---|
| `preorder` | root → left → right |
| `inorder` | left → root → right |
| `postorder` | left → right → root |
| `levelorder` | level by level, left to right |

Do **not** modify `BinaryTree.java` or the test file.

### 1. Compile the main sources

```bash
javac -d out/main src/main/java/BinaryTree.java src/main/java/TreeTraversals.java
```

### 2. Compile the test sources

```bash
javac -cp out/main:junit-platform-console-standalone-1.10.0.jar \
      -d out/test \
      src/test/java/TreeTraversalsTest.java
```

> **Windows** – replace `:` with `;` in all `-cp` arguments:
> ```
> javac -cp out/main;junit-platform-console-standalone-1.10.0.jar ...
> ```

### 3. Run the tests

```bash
java -jar junit-platform-console-standalone-1.10.0.jar \
     execute \
     --class-path out/main:out/test \
     --scan-class-path
```

> **Windows:**
> ```
> java -jar junit-platform-console-standalone-1.10.0.jar execute --class-path out/main;out/test --scan-class-path
> ```

A passing run looks like:

```
Test run finished after ...
[        14 tests found     ]
[         0 tests skipped   ]
[        14 tests started   ]
[         0 tests aborted   ]
[        14 tests successful]
[         0 tests failed    ]
```"# -rbol-Binario" 
