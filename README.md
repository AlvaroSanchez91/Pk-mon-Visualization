In this document we can see a brief visual exploratory of the pokémon
data set provided by kaggle: <https://www.kaggle.com/alopez247/pokemon>.
My first videogame was the blue edition of pokémon, so i decided to do
this analisys only with the first generation data.

We will work with nine features: Name (Bulbasaur, Charmander...),Type of
pokemon (fire, water...), Total (the sum of the numeric features), HP ,
Attack, Defense, Special Attack, Special Defense, and Speed. Lets start
seeing how are distributed those features.

### Histogram of each variable.

![](README_files/figure-markdown_strict/unnamed-chunk-1-1.png)

![](README_files/figure-markdown_strict/unnamed-chunk-2-1.png)

![](README_files/figure-markdown_strict/unnamed-chunk-3-1.png)

![](README_files/figure-markdown_strict/unnamed-chunk-4-1.png)

![](README_files/figure-markdown_strict/unnamed-chunk-5-1.png)

![](README_files/figure-markdown_strict/unnamed-chunk-6-1.png)

![](README_files/figure-markdown_strict/unnamed-chunk-7-1.png)

### Boxplots depending on type.

Now, lets compare the previuos features depending on the type of
pokémon.

![](README_files/figure-markdown_strict/unnamed-chunk-8-1.png)

In general, we can think that ice pokémon are better, but also we can
see some Psychic pokémon with high numbers.

![](README_files/figure-markdown_strict/unnamed-chunk-9-1.png)

Here the ghosts are the worsts, and the normal and fairy seems the best
(we can see two atipical values). Although that, the results are
similar.

![](README_files/figure-markdown_strict/unnamed-chunk-10-1.png)

We can see that fighting pokemon have the best attack, while faiy and
ghost seems the worsts. But we have a high variances in some groups, so
it's dificult to take conclussions.

![](README_files/figure-markdown_strict/unnamed-chunk-11-1.png)

Rock pokemón seems to have the best defense, and ghosts the worst. In
the rest of groups the results are similar, although whe have some
atipical values.

![](README_files/figure-markdown_strict/unnamed-chunk-12-1.png)

We can see that psychics and ghosts have the bests numbers in special
attack, as we expected. We can see that here the variances are quite
low, and the special attack depend on the group.

![](README_files/figure-markdown_strict/unnamed-chunk-13-1.png)

Most of the groups have similar values in special defense, but ice and
psychic (both of them have the bests results). Bug have a really high
variance with a low special defense for some pokémon.

![](README_files/figure-markdown_strict/unnamed-chunk-14-1.png)

Electric and psychic have the highest values in speed (others group have
similar ones), while fairy and ground seems to have the worsts.

### Looking for correlated variables.

We cold try to look for dependencies betwen some variables, lets look
the correlations to see wich variables should we compare.

![](README_files/figure-markdown_strict/unnamed-chunk-15-1.png)

The highes variables are produced by attack with defense, HP with
special defense, and special attack with special defense.

![](README_files/figure-markdown_strict/unnamed-chunk-16-1.png)

![](README_files/figure-markdown_strict/unnamed-chunk-17-1.png)

![](README_files/figure-markdown_strict/unnamed-chunk-18-1.png)

We can see just a little dependencie between the variables, maybe due to
the level of the pokémons. When the pokémons evolve, they increase their
numbers.
