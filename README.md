# Test case for build error

### To reproduce error

1. Clone this repository
1. Run `npm intall` to install Fractal
1. Run `fractal build`

The build process should then fail with an faral error (`Ineffective mark-compacts near heap limit Allocation failed - JavaScript heap out of memory`)

If you remove one item from the context of component "buttonGroup", the build process wiull finish without errors.
