# Square Root Computation

## Add Your Name Here

## Program Output

### Use two fenced code blocks to provide output from two different runs of `squareroot` with the same input

TODO: Pick a single input value and run it with:
(a) the exhaustive algorithm
and
(b) the efficient algorithm

TODO: Make sure that you pick a sufficiently large and representative input value!

#### One output from running the exhaustive algorithm

TODO: Provide the specific command that you ran to produce this output
TODO: Use a fenced code block to provide the output for this command.

- `poetry run primality --number 49979687 --approach efficient --profile`

#### One output from running the efficient algorithm

TODO: Provide the specific command that you ran to produce this output
TODO: Use a fenced code block to provide the output for this command.

- `poetry run squareroot --number 25000 --approach efficient --profile`

## Performance Analysis

TODO: Provide paragraph(s) that state which algorithm is fastest. Please make
sure that you reference your program output to explain the results. If there are
anomalies in your data sets produced by `squareroot` then make sure that you
explain them to the best of your ability, leveraging the content in the course
textbook and any online resources you want to reference. Importantly, you must
describe both (a) the trends in the data set and (b) why those trends are evident.

## Source Code

### Describe in detail how the completed source code works

#### A source code segment that performs profiling on `compute_square_root_exhaustive`

TODO: Use a fenced code block to provide the requested source code
TODO: Write at least one paragraph to explain the request source code

```
profiler.start()
square_root_tuple = compute_square_root_exhaustive(number)
profiler.stop()
```

#### The declaration of the default value of the `square_root_tuple`

TODO: Use a fenced code block to provide the requested source code
TODO: Write at least one paragraph to explain the request source code

```
square_root_tuple: Tuple[bool, float, int] = (False, 0.0, 0)
```

## Professional Assessment

### What are your strengths and weaknesses in the area of writing good commit messages?

TODO: Provide a one-paragraph response that answers this question in your own words.

### What are your strengths and weaknesses in the area of write good source code comments?

TODO: Provide a one-paragraph response that answers this question in your own words.
