Have you ever wondered how many ways can we do arithmetic to get an answer of, say, 5?

Well, this question is pretty vague, so let's set up some rules.

Let's say we want to combine 3 positive integers by addition, subtraction & multiplication to get an answer of 5.

But how high should they go? If we set a limit of 3, we get 20 possibilities:

```
1 + 1 + 3 = 5
1 + 2 + 2 = 5
1 + 2 * 2 = 5
1 * 2 + 3 = 5
1 + 3 + 1 = 5
1 * 3 + 2 = 5
2 + 1 + 2 = 5
2 + 1 * 3 = 5
2 * 1 + 3 = 5
2 + 2 + 1 = 5
2 * 2 + 1 = 5
2 + 3 * 1 = 5
2 * 3 - 1 = 5
3 + 1 + 1 = 5
3 + 1 * 2 = 5
3 * 1 + 2 = 5
3 - 1 + 3 = 5
3 + 2 * 1 = 5
3 * 2 - 1 = 5
3 + 3 - 1 = 5
```

You can check all those in a calculator, all those expressions really do equal 5.

We can also adjust every parameter, & get wildly different results! This generator follows the BODMAS convention (so multiplication takes precedence over addition & subtraction).

Does this generator take order into account? Yes. `5 + 2` & `2 + 5` are counted as different entries, even though they have the same value.

You can also find partitions or factors of a number using this tool, although high numbers become very slow.
