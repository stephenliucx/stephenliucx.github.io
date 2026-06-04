+++
date = '2026-06-03T23:50:29-04:00'
title = 'Segre'
+++

## Segre embedding

Here is a Sage box.

{{< sagecell >}}
var('x, y, z')
G=implicit_plot3d(x*y==z, (x,-1,1), (y,-1,1), (z,-1,1),smooth=True, plot_points=60)
G.show()
{{< /sagecell >}}

Hmmm.