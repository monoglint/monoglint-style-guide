# monoglint-style-guide

**biggest thing to get out of this**
- PREFIXES ONLY CLASSIFY TYPES. DO NOT USE PREFIXES FOR CASUAL VARIABLE NAMES OR LITERALLY ANYTHING ELSE. DON'T BE LAZY AND MAKE YOUR CODE MAKE SENSE
```cpp
using t_node_ptr = std::unique_ptr<node>;

enum e_success : bool {
  SUCCESS = true,
  FAILURE = false,
};

int main() {
  std::cout << "Hello world\n";

  // No prefixes are used incorrectly here. 
  t_node_ptr if_stmt_node = parse_if_stmt();

  e_success lex_success = lex_source_code("blah");
}

```

**namespaces**
- Namespace contents require an indent.
- Title namespaces in snake_case.

**all types**
- Title all types (classes, structs, typedefs, enums) in snake_case.
- Prefix all type names.
- **classes**:         c_
- **structs**:         s_
- **using/typedefs**:   t_
- **enums**:           e_

**variables & properties**
- all of this in snake case too
- DO NOT USE PREFIXES IN VARIABLE NAMES
- but what if-
  NO


**functions & methods**



