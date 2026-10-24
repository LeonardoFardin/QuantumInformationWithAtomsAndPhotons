
The drive is a monochromatic laser. Moving to a frame rotating at the laser frequency makes the Hamiltonian time-independent, and cavity losses enter through the collapse operator `sqrt(κ) a`.

## What is studied

1. **Uncoupled case** (`g = 0`, laser resonant with the cavity). The cavity reaches a **coherent state**. The photon-number distribution of the numerical steady state matches the Poisson distribution of a coherent state with the target mean photon number. The drive amplitude `ε = κ sqrt(n_target) / 2` is inferred from the Bloch optical equations.
2. **Laser resonant with the lower dressed state** (`ω = ω0 − g`). The photon number dynamics are analysed as a function of the drive strength, the coupling `g` and the decay rates `κ`, `γ`.
3. **Perturbative treatment of the drive.** There is no first-order correction. The second-order coupling between the dressed states is small compared with their splitting (`H(2)/ΔE ~ α² ≪ 1` for `ε = αg`), which justifies the blockade picture.
4. **Second-order correlation function** `g(2)`, both in time and at zero delay as a function of the probe detuning. It shows antibunching (`g(2)(0) < 1`) at the dressed-state resonances `ω_p − ω0 = ±g` and strong bunching at the bare cavity frequency.
5. **Analytical steady states** from the equations of motion of the mean values. The uncoupled case has a closed-form solution. For the coupled case a mean-field factorization (`<σ+ a> = <σ+><a>`) gives a nonlinear system that has to be solved numerically.

## Repository structure

* Notebooks with the QuTiP simulations and the analytical comparisons.
* `Cavity_blockade_a_way_to_make_photons_interact.pdf`: the presentation.

## How to run

Install the required dependencies (`numpy`, `scipy`, `matplotlib`, `qutip`) and run the notebooks using Jupyter.
