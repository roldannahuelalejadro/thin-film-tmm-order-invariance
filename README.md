# Thin-Film TMM Order Invariance

This repository contains the source and compiled preprint:

**Condición de conmutación e invariancia de orden en stacks dieléctricos bimateriales bajo polarización TM**

The work derives a sufficient condition under which the characteristic transfer matrices of two dielectric materials commute independently of their layer thicknesses. In this limit, the optical response of an arbitrary bimaterial stack loses its dependence on layer order and can be represented through accumulated phase variables.

## Main result

For TM polarization, the structural commutation condition leads to

```text
theta_ab = arcsin[n_H n_L / (n_0 sqrt(n_H^2 + n_L^2))].
```

The derivation starts from Maxwell's equations, constructs the characteristic matrix of a layer, evaluates the matrix commutator, and states the assumptions under which the reduction is exact.

## Files

- `paper.tex`: self-contained LaTeX source.
- `paper.pdf`: compiled preprint.
- `CITATION.cff`: citation metadata.
- `LICENSE.md`: CC BY 4.0 licensing information.

## Compilation

Compile the document twice to resolve cross-references:

```bash
pdflatex -interaction=nonstopmode -halt-on-error paper.tex
pdflatex -interaction=nonstopmode -halt-on-error paper.tex
```

## Resumen

El trabajo deriva una condición suficiente para que las matrices características de dos materiales dieléctricos conmuten con independencia de sus espesores. En ese punto, la respuesta del stack depende de fases acumuladas y resulta invariante frente a permutaciones de las capas. El documento distingue esta condición estructural de las conmutaciones accidentales que pueden aparecer para fases o espesores particulares.

## Author

Nahuel Alejandro Roldán  
Consejo Nacional de Investigaciones Científicas y Técnicas (CONICET)  
ORCID: [0009-0009-6747-0756](https://orcid.org/0009-0009-6747-0756)

## License

The preprint and its source are released under the [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).
