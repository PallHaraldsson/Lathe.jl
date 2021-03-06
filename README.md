<div align="center"><img src="https://github.com/emmettgb/Lathe.jl/blob/Unstable/lathelogo.png" />
  <h2>0.1.1 "ButterBall"</h2>
</div>
<div align="left">
  <p> Lathe.jl is an all-in-one package for predictive modeling in Julia. It comes packaged with a Stats Library, DataFrame tools, Preprocessing, Machine-Learning Models, and Model Validation. Lathe features easy one line constructor model fit-predicting, fast dispatch, easy documentation, and a great code-base with strong deployability.</p>
        </div>
        </div>
      </a> </br></br></br>
      <h3>Documentation<h3>
  
  
  
  **You can access Lathe documentation using the built in ?() method in Julia:**
  
  
```julia
help?> Lathe.stats.mean
  Calculates the mean of a given array.

  ──────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────────

  array = [5,10,15]

  mean = Lathe.stats.mean(array)

  println(mean)

  10

```
## Features
- Pipelines
- An ever-expanding library of models for predicting continous features, and soon categorical features.
- Easy! Machine learning is simplified! Lathe makes it possible to fit and predict in just two lines!
- Internal documentation - use the ?() function on anything and get all the information you need.
- Stats library with distributions, tests, and base statistics.
- Easy Train Test Split in one line.
- Simplified Preprocessing, with most scalars being simple
- Expandable, dependable, and reliable. Lathe has a big advantage in being written in Julia. Many functions, notably the prediction function utilize Julia's function struct dispatch syntax, allowing end users to quickly modify the function in their environment to make it work for them. This also adds to the long term support, as anyone could develop a model for Lathe, even entirely seperately using Lathe as a code-base to work off of.
- Serialization for pipelining, using one prediction function.
- A small, and expanding distributions library.
## Add it!
LTS 
 ```julia
 using Pkg; Pkg.add("Lathe")
 ```
 Unstable
 ```julia
 using Pkg; Pkg.add("Lathe"#Unstable)
 ```
