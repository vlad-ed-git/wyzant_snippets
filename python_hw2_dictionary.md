# Homework: Reading Shoe Store Data

The dictionary below represents product data from an online shoe store. Each shoe has a unique product ID, such as `"SHOE-1001"`.

```python
shoes = {
    "SHOE-1001": {
        "name": "Cloud Runner 2",
        "brand": "NorthPeak",
        "color": "White",
        "price": 89.99,
        "material": "Mesh",
        "rating": 4.6,
        "available_sizes":,[8][9][10][11][12]
    },
    "SHOE-1002": {
        "name": "City Leather Loafer",
        "brand": "Marston",
        "color": "Dark Brown",
        "price": 124.50,
        "material": "Leather",
        "rating": 4.3,
        "available_sizes":,[8][9]
    },
    "SHOE-1003": {
        "name": "Trail Grip Pro",
        "brand": "SummitWay",
        "color": "Forest Green",
        "price": 109.99,
        "material": "Synthetic",
        "rating": 4.8,
        "available_sizes":,[8][11][12]
    },
}
```

## Questions

### Question A

Print the name of the shoe with the ID `"SHOE-1002"`.

### Question B

Print the price of the shoe with the ID `"SHOE-1003"`.

### Question C

For `"SHOE-1001"`, print each available shoe size that is greater than `8`.

<details>
<summary>Click to see a hint for Question C</summary>

First, retrieve the `available_sizes` list for the shoe and store it in a variable named `sizes`.

```python
sizes = shoes["SHOE-1001"]["available_sizes"]
```

Then, use a `for` loop to go through each size. Inside the loop, write an `if` statement that checks whether the size is greater than `8`.

Print only the sizes greater than `8`.

```python
for size in sizes:
    if ???:
        print here
```

</details>
