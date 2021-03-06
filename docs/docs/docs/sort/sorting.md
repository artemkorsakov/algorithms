---
layout: docsplus
title: "Sorting Algorithms"
realization: sort/Sorting.scala
---

[Sorting algorithms](https://en.wikipedia.org/wiki/Sorting_algorithm)

### insertionSort
[Insertion sort](https://en.wikipedia.org/wiki/Insertion_sort).

**Algorithm**

**Complexity** _O_(n<sup>2</sup>)
     
**Sources** 
- [Insertion sort](https://en.wikipedia.org/wiki/Insertion_sort)

**Using**
```scala mdoc
import com.github.artemkorsakov.sort.Sorting._
{
  val array = Array(5, 2, 4, 6, 1, 3)
  insertionSort(array)
  array
}
```

---

### insertionSortReverse
[Insertion sort](https://en.wikipedia.org/wiki/Insertion_sort).

**Algorithm**

**Complexity** _O_(n<sup>2</sup>)
     
**Sources** 
- [Insertion sort](https://en.wikipedia.org/wiki/Insertion_sort)

**Using**
```scala mdoc
{
  val array = Array(5, 2, 4, 6, 1, 3)
  insertionSortReverse(array)
  array
}
```

---

### selectionSort
[Selection sort](https://en.wikipedia.org/wiki/Selection_sort).

**Algorithm**

**Complexity** _О_(n<sup>2</sup>) comparisons, _О_(n) swaps
     
**Sources** 
- [Selection sort](https://en.wikipedia.org/wiki/Selection_sort)

**Using**
```scala mdoc
{
  val array = Array(5, 2, 4, 6, 1, 3)
  selectionSort(array)
  array
}
```

---

### selectionSortReverse
[Selection sort](https://en.wikipedia.org/wiki/Selection_sort).

**Algorithm**

**Complexity** _О_(n<sup>2</sup>) comparisons, _О_(n) swaps
     
**Sources** 
- [Selection sort](https://en.wikipedia.org/wiki/Selection_sort)

**Using**
```scala mdoc
{
  val array = Array(5, 2, 4, 6, 1, 3)
  selectionSortReverse(array)
  array
}
```

---

### mergeSort
[Merge sort](https://en.wikipedia.org/wiki/Merge_sort).

**Algorithm**

**Complexity** _О_(n<sup>2</sup>) comparisons, _О_(n) swaps
     
**Sources** 
- [Merge sort](https://en.wikipedia.org/wiki/Merge_sort)

**Using**
```scala mdoc
{
  val array = Array(5, 2, 4, 6, 1, 3)
  mergeSort(array)
  array
}
```

---