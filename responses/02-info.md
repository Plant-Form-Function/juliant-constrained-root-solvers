Good job! Though branch protection is not mandantory, it is highly recommended
to apply similar rules. Futher, you may add more protection rules, such as
adding more tests, you may learn this in other courses.

Now, it is time to create a few functions to test:

1. `f_1(x) = (x-2)^2 - 1`
2. `f_2(x) = (x-1)^2 + 1`
3. `f_3(x) = -1 - (x-1)^2`

Here are the steps:

1. Still make changes on your unprotected branch
2. Define the three functions in `src/MyLearning.jl` within the module
   `MyLearning` (after `module MyLearning`, and before `end`)
3. Export the defined functions by adding `export` fields
4. Once you are done, commit the changes

Example:

```julia
module MyLearning

# export the function as public functions
export g_1, g_2

# method 1
function g_1(x)
    return x^2
end

# method 2
g_2(x) = x^2;

end # module
```
