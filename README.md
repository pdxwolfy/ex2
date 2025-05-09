Here's a bunch of text.

```python
NUMBER_WORDS = ['zero', 'one', 'two', 'three', 'four', 'five',
                'six', 'seven', 'eight', 'nine', 'ten', 'eleven',
                'twelve', 'thirteen', 'fourteen', 'fifteen',
                'sixteen', 'seventeen', 'eighteen', 'nineteen']

def word_for_number(num):
    return NUMBER_WORDS[num]

def alphabetic_number_sort(numbers):
    return sorted(numbers, key=word_for_number)
```

And some more text.
