# sar_backprojection
Implements a SAR image formation pipeline using backprojection.

## Structure
* data : Raw data to process.
* src : MATLAB source code
* submodule : External libraries added as submodules. This includes the NGA `MATLAB_SAR` toolbox.
* test : Unit tests for source code in `src`

### Submodules

Before using the `MATLAB_SAR` toolbox, you must run

```bash
git submodule update --init --recursive submodule
```
