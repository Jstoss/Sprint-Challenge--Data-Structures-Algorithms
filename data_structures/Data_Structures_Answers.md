Add your answers to the questions below.

1. What is the runtime complexity of your `depth_first_for_each` method?

  O(n), it's executing a callback on every node, so as the tree grows, the runetime grows as well

2. What is the space complexity of your `depth_first_for_each` function?

  O(n) where n is the length of the longest path

3. What is the runtime complexity of your `breadth_first_for_each` method?

  O(n), for the same reason as depth first

4. What is the space complexity of your `breadth_first_for_each` method?

  O(n), is the tree level with the most sub nodes

5. What is the runtime complexity of your `heapsort` function?

  O(n log n), it builds a heap based off an array of n length, and then every
  time the max is taken off, it runs the log n sifting, decreased in length

6. What is the space complexity of the `heapsort` function? Recall that your implementation should return a new array with the sorted data. What would be the space complexity if your function instead altered the input array?

  O(c), the heap and the function controlling the sort both have an array, but
  it's moving values from one to the other.

  If it was changing the inputted array instead of returning a new one, it still wouldn't change the space complexity, as another array would still be required for removing the max and creating a new sift. A heap doesn't store in max to least, only that the parent is the max of both children
