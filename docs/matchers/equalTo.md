# [`equalTo`](https://github.com/npryce/hamkrest/blob/9ce6f5882203b97130d1e85fa10818cbce1b7693/src/main/kotlin/com/natpryce/hamkrest/core_matchers.kt#L18-L27)

A simple matcher that asserts equality. Works with `null` just like Kotlin's `==` operator.

### Assertion

```
assertThat("one", equalTo("two"))
```

### Test Output

```
expected: a value that is equal to "two"
but was: "one"
```




