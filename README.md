### Array Iterators

I. See the following array:
```ruby
candies = ['twix', 'smarties', 'reeses pieces', 'snickers', 'three musketeers', 'milky way', 'swedish fish', nil, 1, 2]
```

Write a method that will accept this array as an argument and transform it into an array that looks like this:

```ruby
candies = ['Twix', 'Smarties', 'Reeses Pieces', 'Snickers', 'Three Musketeers', 'Milky Way', 'Swedish Fish']
```
This means your method should do three things:

1. Capitalize each candy name
2. Remove each number
3. Remove the nil value

Now we want an inventory of all of the candies, each candy should only be listed one time

II. Array Methods Checklist
```
map, each, find, select, detect, compact, uniq, split, join
```

Consider the array methods above. Be sure to check out the Ruby documentation if you're unfamiliar with what they do!

Fill in the cheat sheet below, placing each iterator in it's correct location. The first two (`each` and `map`) have been completed.

A. If I want operate on each element in the array

  1. And do an operation

      --> `each`

  2. And modify each element

      --> `map`

B. If I want to reduce the number of elements in the array

   1.
     -->

   2.
     -->

   3.
     -->

   4.
     -->
