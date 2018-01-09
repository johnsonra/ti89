# Ti 89 functions

This repo contains some statistics functions for my old Ti 89 (nearly 20 years old). I think the new ones might have some of this functionality built in.

## pchisq(c,d)
Computes the p-value for the critical value, *c*, from a Chi-squared distribution with *d* degrees of freedom.

## pnorm(x,μ,σ)
Computes the two tailed p-value for the critical value, *x*, from a normal distribution with mean, *μ*, and standard deviation, *σ*.

## pt(x,d)
Computes the two tailed p-value for the critical value, *x*, from a t distribution with *d* degrees of freedom.

## pz(z)
Computes the two tailed p-value for the critical value, *z*, from a normal distribution with mean, 0, and standard deviation, 1.

## Γ(z)
This is an approixmation of the gamma function as defined [here](http://www.rskey.org/CMS/8-programmable-calculators?start=268). I made a few small edits and left a couple of lines out (e.g. I'm not going to use this for imaginary numbers). This is an approximation, but it is more than accurate enough for my needs.

Called by:
* pchisq()
* pt()
