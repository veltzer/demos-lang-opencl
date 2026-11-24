# TOFIX

Findings from a code scan on 2026-10-04.

## Medium

- `config/project.lua:3` - the repo is described as "Demos for OpenCL" but contains no OpenCL code at all (only `README.md`, `doc/links.txt` and shared fleet files); either add the demos (kernels, host programs, a build) or retire the repo.
- `doc/links.txt:3` - link is dead (404): the upstream directory is `square_array`, not `squeare_array`; change it to `https://github.com/rsnemmen/OpenCL-examples/blob/master/square_array/clbuild.c`.

## Low

- `README.md:2` - README is a single line repeating the description; once content exists, describe the demos and how to build/run them, and reference `doc/links.txt`.
