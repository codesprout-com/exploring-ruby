# 5 fun and useful `Array` methods

### Want to keep learning more? Join [CodeSprout](https://www.codesprout.com/)!

The mantra over at CodeSprout is KAIZEN! Continuously learn, continuously improve. [Sign up for free](https://www.codesprout.com/users/sign_up)!

### Description

Ruby's `Array` class has some powerful and fun methods that you can use to be super-productive.

Here's some code from a video on the [CodeSprout YouTube channel](https://www.youtube.com/@codesprout) that showcases some of the most used methods you can find on instances of `Array`.

The code in the YouTube videos uses Ruby 3.1.3. Check out [the official Ruby documentation](https://ruby-doc.org/3.1.3/Array.html) for 3.1.3 for more details and more goodness.


### Methods

#### 1. `#map`

Calls the block, if given, with each element of `self`; returns a new Array whose elements are the return values from the block.

#### 2. `#combination`

Calls the block, if given, with combinations of elements of `self`; returns `self`. The order of combinations is indeterminate.

When a block and an in-range positive Integer argument `n` (`0 < n <= self.size`) are given, calls the block with all n-tuple combinations of `self`.

#### 3. `#shuffle`

Shuffles the elements of `self` in place.

#### 4. `#join`

Returns the new String formed by joining the array elements after conversion. For each element `element`.

#### 5. `#keep_if`

Retains those elements for which the block returns a truthy value; deletes all other elements; returns `self`.
