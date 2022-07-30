#### fermionic-parakeet

# **Implementing Jordan-Wigner & Bravyi-KItaev Transforms using OpenFermion Library**

##### Implement the Jordan-Wigner &amp; Bravyi-Kitaev transforms

### **Setup**

Install the OpenFermion Python package using ```pip```:
```console
python3 -m pip install --user openfermion
```

Install latest version in (development mode):
```console
git clone https://github.com/quantumlib/OpenFermion
cd OpenFermion
python3 -m pip install -e .
```

### **Jordan-Wigner Transform**

The Jordan–Wigner transformation maps spin operators onto fermionic creation and annihilation operators. Originally it was proposed by Pascual Jordan and Eugene Wigner for one-dimensional lattice models, but now two-dimensional analogues of the transformation have also been created. The Jordan–Wigner transformation is often used to exactly solve 1D spin-chains such as the Ising and XY models by transforming the spin operators to fermionic operators and then diagonalizing in the fermionic basis.

This transformation actually shows that the distinction between spin-1/2 particles and fermions is nonexistent. It can be applied to systems with an arbitrary dimension. 

### **Bravyi-kitaev Transform**

Bravyi–Kitaev transformation is typically at least approximately as efficient as the canonical Jordan–Wigner transformation and results in substantially reduced gate count estimates when performing limited circuit optimizations.

Performed as a [tutorial](https://quantumai.google/openfermion/tutorials/jordan_wigner_and_bravyi_kitaev_transforms)
