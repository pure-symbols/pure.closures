# *pure project* 🧫

~~~
🧫 implement all by nothing but only lexical closure . 🧬
~~~

## Intro

This is a theoretical verification in *Functional Programming* studies.

The only one necessary thing of a language for this pure project is a ***lexical closure*** feature, means it band its *free variables* by the *lexical scoping*, not the *dynamic scoping*, and this also called ***closure*** or ***function closure***. That means there is a *first-classed function means all function is valve* and *it will pick all the symbol **where it be defined** which is needed by it-self*. With out such thing, all of this projec shall not works.

And with such feature, we can make these things: 

- *Laziness* -- without *lexical closure* feature, then we'll must get the *laziness* just from a language design and implementation.
- *Currying* -- if we don't have the *closure* feature, then we cannot do any *currying* things that means no *(elegant) pipe* then I shall give up this *pure project* at its begin.
- *Tuple* -- we can get numbers of values and let them applies one by one onto a picker, and then we just give a specific picker to get the specific value we've just given in.
- *...* -- ...


## Documents

- [*Let's See what the Lambda Calculus is ☄️*](./.docs/lambda-calculus-101)
- [Some thing about the Fixed-point Combinators 🦠](./.docs/fixed-point-things)


## Thanks for

- [*CS3110*](https://cs3110.github.io/textbook/chapters/hop/higher_order.html?highlight=pipe) from [*Cornell University*](https://www.cs.cornell.edu/courses/cs3110/)
- *ISMISM* courses by *Liu Si Mo* also called *Wei Ming Zi*
- *Lacanian Psychoanalysis* theory from the *Lacanianists*
- *Dialectic* or *Logic* method from *Georg Wilhelm Friedrich Hegel*, *Karl Marx* and the *Leninists*
- *Lambda Calculate* from *Alonzo Church* and *Currying* theory
- *Lexical Closure* feature that provide this project almost
- The [*Functional Programming For The Rest of Us | defmacro*](https://www.defmacro.org/2006/06/19/fp.html) which told me the *CPS Programming*
- *Rain World* game which give me some idea for the names


## Implementations

- [ ] [TypeScript](./pure.ts)
- [ ] [Rust](./pure.rs)
- [ ] [Java](./pure.java)
- [ ] ...

