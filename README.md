# F# Mutable Variable Swap Bug

This repository demonstrates a common issue encountered when working with mutable variables in F#. The `swap` function, seemingly designed to exchange the values of two mutable variables, produces unexpected results. The issue lies in the function's inability to modify the original variables passed as arguments.