---
date: 2023-06-07
categories:
- foobar
---

# The relation between the UI and its ViewModel

There is this link I've been exploring between `Views` and their `ViewModels`.
But nowadays `View` is a bad word in Android so let's call it `UI`.

I'll complete this entry later, now I'm just checking code formatting.

```kotlin
@Composable
public fun NoKotlin() {
    Log.d("Foo", "Bar")
}
```

```Kotlin
@Composable
public fun UpperCaseKotlin() {
    Log.d("Foo", "Bar")
}
```

```kotlin
@Composable
public fun LowerCaseKotlin() {
    Log.d("Foo", "Bar")
}
```