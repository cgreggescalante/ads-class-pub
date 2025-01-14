# Order! Order!

Complete class _OrderedList_ and implement the following methods. Remember that you cannot simply append to an ordered list. `append()` and `insert()` methods should call `add()` to properly update the list.

1. Implement method `append(item)` of the _OrderedList_ class to add a new item to the end of the list.
2. Implement method `insert(position, item)` of the _OrderedList_ class to insert a new item to the specified position.
3. Implement method `index(item)` of the _OrderedList_ class to retrieve the position of an item in the list or -1 if not there.
4. Implement method `pop(position)` of the _OrderedList_ class to remove the specified (or the last) item and return its value.
5. Implement a magic method `__getitem__` for the OrderedList class. It allows using a subscript (e.g. `my_list[160]`) to retrieve a specific item (node) of a list.

## What to do

`python3` should be `python3.9` or newer.

- Read _exercises/orderedlists/orderedlists\_description.md_ (this file).
- Modify and run _exercises/orderedlists/orderedlists.py_.

```bash
python3 exercises/orderedlists/orderedlists.py
```

- Compare your output to that provided in _exercises/orderedlists/orderedlists\_output.txt_.
- Test your implementation.

```bash
python3 -m pytest exercises/orderedlists/orderedlists_test.py
```
