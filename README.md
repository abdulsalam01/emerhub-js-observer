# emerhub-js-observer
Quick optimalization solution and low process based on given problem

## Poblem statement
Please write code to change `seconds_batches` to be `sorted_uniq_seconds` in simplest way in Javascript

```const seconds_batches = [
  [1, 2, 3, 4],
  [1, 2, 3, 4, 5, 6, 7],
  [30, 31, 32, 33],
  [1, 2, 3, 32, 33, 34, 35, 36, 37, 38, 39, 40],
]

const sorted_uniq_seconds = [1, 2, 3, 4, 5, 6, 7, 30, 31, 32, 33, 34, 35, 36, 37, 38, 39, 40]
```

## Solution
Using `Set` as main data structure and flatten array using `O(1)` as space complexity