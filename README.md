# Probabilite_avec_OCaml
Calcul de probabilités avec OCaml (Monte Carlo)

# Probabilite_avec_OCaml
Calcul de probabilités avec OCaml (Monte Carlo)

<h1>TD de probabilités avec OCaml</h1>

Liste d'exercices de probabilités résolus avec OCaml.

Les fichiers sont au format .ipynb (Notebook de Jupyter). 

Le kernel <tt>IOCaml</tt> s'installe sur Jupyter ainsi:
<pre>
opam init
opam switch 4.0x.y // x=version y=subversion
eval $(opam config env)
opam install iocaml
</pre>

Alternativvement, le kernel <tt>ocaml-jupyter</tt> s'installe ainsi:
<pre>
opam depext conf-gmp.1
opam install jupyter
opam install jupyter-archimedes
jupyter kernelspec install --name ocaml-jupyter "$(opam config var share)/ocaml-jupyter"
</pre> 

Pour les graphiques, <tt>plplot</tt> s'installe ainsi:
<pre>
opam switch 4.0x.y // x=version y=subversion
eval $(opam config env)
opam install depext
opam depext plplot
opam install plplot
</pre>
