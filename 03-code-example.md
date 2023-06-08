# Trying out codeblocks

## Python codeblock

```{code-block} python
:name: my-program
:caption: Creating a TensorMesh using SimPEG
from discretize import TensorMesh

hx = [(1, 40)]
hy = [(1, 40)]

mesh = TensorMesh([hx, hy])
```

In the [](#my-program), we create a mesh for simulation using [SimPEG](https://discretize.simpeg.xyz/).

## KaTeX example

````{prf:lemma}
:label: my-lemma

If $\hat P$ is the fixed point of the map $\mathcal B \circ \mathcal D$ and $\hat F$ is the robust policy as given in [(7)](https://python-advanced.quantecon.org/robustness.html#equation-rb-oc-ih), then

```{math}
:label: rb_kft

K(\hat F, \theta) = (\theta I - C'\hat P C)^{-1} C' \hat P  (A - B \hat F)
```
````
