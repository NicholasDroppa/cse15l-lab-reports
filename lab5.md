# Part 1
### failure-inducing input:

```
	@Test 
	public void testReverseInPlaceFailure()
  {
    int[] input1 = { 3, 5, 4, 7, 6 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 6, 7, 4, 5, 3 }, input1);
	}
```

### successful input:

```
	@Test 
	public void testReverseInPlaceSuccess()
  {
    int[] input1 = { 3, 2, 1, 2, 3 };
    ArrayExamples.reverseInPlace(input1);
    assertArrayEquals(new int[]{ 3, 2, 1, 2, 3 }, input1);
	}
```
