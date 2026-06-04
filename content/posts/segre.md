+++
date = '2026-06-03T23:50:29-04:00'
title = 'Algebraic surfaces'
+++

## Segre embedding

Here is the affine part of the $\mathbb{R}$-points of the embedding of $\mathbb{P}^1\times\mathbb{P}^1$ into $\mathbb{P}^3$.

{{< sagecell >}}
var('x, y, z')
G=implicit_plot3d(x*y==z, (x,-1,1), (y,-1,1), (z,-1,1),smooth=True, plot_points=60)
G.show()
{{< /sagecell >}}

{{< sagecell >}}
var('x, y, z')
G=implicit_plot3d(x^4+y^4+z^4-x^2-y^2-z^2-x^2*y^2-x^2*z^2-y^2*z^2+1==0 , (x,-2,2), (y,-2,2), (z,-2,2),smooth=True, plot_points=60)
G.show()
{{< /sagecell >}}

Hmmm. 