##  Prediction Tools

Summary -- Deliver a first set of prediction tools for the mass function, the matter power spectrum, the
concentration-mass relation, and the galaxy correlation function, including massive neutrinos and a dynamical
dark energy equation of state. Cosmological parameters and ranges have been specified for this task taking
into account accuracy requirements for DC1 and available computing resources.

### Key Tasks
* Key Task CS6.1.1 ( 06/16 ): Carry out simulations following the strategy described in
Heitmann et al. (2015).
* Key Task CS6.1.2 ( 09/16 ): Extract prediction tools using emulator techniques.
* Key Task CS6.1.3 ( 09/16 ): Explore alternative methods.
* Key Task CS6.2.1 ( 12/16 ): Generate document that lists all requirements for DC2/DC3

#### Suggested organization
Repositories are available per deliverable.  Each key task has a subdirectory.
We have a `source` directory in each key task area for any supporting
code that goes with an effort.  There will also be a `doc` directory to hold documents in markdown,
latex, or binary formats.  The idea is to version everything and give us a good way to diff things.

Each deliverable is slightly different, so these repositories should grow to support the different need.

Please feel free to use github issues on each repository to organize work.

#### Progress so far
* The first set of 36 simulations that are required to build the first generation of emulators has been finished. We are currently working on extracting prediction tools for the matter power spectrum, the halo mass function, and bias measurements (we are also extracting RSD measurements which are not very relevant for DESC).
