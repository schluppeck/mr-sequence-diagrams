
# exploring a `javascript/d3` port some `metapost` code


# Original documentation of this repository

h/t https://github.com/dangom/mr-sequence-diagrams

[original readme file](_README.org)

## tl;dr

- make sure ``metapost`` is intalled (for me, via TeXLive)

```bash
mpost seq.mp
```

- ``convert`` can handle `.mps` files. E.g.

```bash
convert -density 300 input.mps output.png
```

- for straight to LaTeX, use `graphicx` package and add a `\includegraphics{input.mps}`
-

## Example images (original)

###  FID Acquisition
<img src="./images/figs-0.png" width=300px>



### Spin Echo Fragment
<img src="./images/figs-1.png" width=300px>

### Gradient Echo Fragment

<img src="./images/figs-2.png" width=300px>

### Slice Selection Fragment
<img src="./images/figs-3.png" width=300px>


### Readout Encoding Fragment
<img src="./images/figs-4.png" width=300px>

### Phase Encoding Fragment with Spin Echo
<img src="./images/figs-5.png" width=300px>

### Multislice SE volume acquisition
<img src="./images/figs-6.png" width=300px>

## 3D GRE with EPI Factor 3
<img src="./images/figs-7.png" width=300px>

# Echo Symbol
<img src="./images/figs-100.png" width=300px>
