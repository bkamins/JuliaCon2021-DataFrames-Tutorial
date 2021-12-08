# JuliaCon2021 DataFrames.jl Tutorial

This is a tutorial on [DataFrames.jl](https://github.com/JuliaData/DataFrames.jl)
prepared for [JuliaCon2021](https://juliacon.org/2021/).

A video recording of the tutorial is available [here](https://www.youtube.com/watch?v=tJf24gfcSto).

In order to run the tutorial make sure that you have Julia executable installed.
The tutorial was updated to Julia 1.7.0 and DataFrames.jl 1.3.0.

To check the version presented during JuliaCon 2021 please check out
this [commit](https://github.com/bkamins/JuliaCon2021-DataFrames-Tutorial/commit/9cdbb80e41c7f11b9e777d91ff394e40de6162b7)
from the repository.

Then the simplest way to run it is to proceed as follows:
1. Clone the
   [tutorial repository](https://github.com/bkamins/JuliaCon2021-DataFrames-Tutorial)
   to a local folder on your computer.
2. Start Julia in your local folder using the `julia --project` command.
3. Run the following commands:
```
using Pkg
Pkg.instantiate()
Pkg.status()
```
The last command should produce the following output:
```
  [e28b5b4c] Bootstrap v2.3.3
  [336ed68f] CSV v0.9.11
  [324d7699] CategoricalArrays v0.10.2
  [8be319e6] Chain v0.4.10
  [a93c6f00] DataFrames v1.3.0
  [38e38edf] GLM v1.5.1
  [7073ff75] IJulia v1.23.2
  [91a5bcdd] Plots v1.25.1
  [f3b207a7] StatsPlots v0.14.29
```
4. Start Jupyter Notebook with:
```
using IJulia
notebook(dir=pwd())
```
5. In the Jupyter Notebook open the *Tutorial.ipynb* file and follow the tutorial.

Steps 3 and 4 need to be run only once. They are intended to make sure that
you have the required packages properly instantiated.

You can find more tutorials on
[DataFrames.jl](https://github.com/JuliaData/DataFrames.jl)
in its
[documentation](https://dataframes.juliadata.org/stable/)
and in
[my blog](https://bkamins.github.io/).
