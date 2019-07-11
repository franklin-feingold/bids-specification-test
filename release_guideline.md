This document captures guidelines to follow when considering a new release of the BIDS specification.

BIDS has generally followed a semantic versioning (semver) approach.
The canonical semver text can be found at [https://semver.org/](https://semver.org/), and an adaptation to documents can be found at [https://semverdoc.org/](https://semver.org/).
A specification falls somewhere between these two, so we should consider carefully the rules.

In both cases, edition numbers are specified as MAJOR.MINOR.PATCH, and the difference is in the rules for incrementing each edition number.

In BIDS, we have considered a major release version (the next being 2.0.0) to indicate backwards incompatible changes, and minor and patch releases must be backwards compatible.

Once a decision for a release has been established, the rules of [decision-making](DECISION-MAKING) govern the mechanism of doing the release (i.e. waiting 5 business days to merge).

**When it is time for a minor (1.X) release?**

This release should be reserved for when a modality (BEP) has been merged into the specification.
Special cases can override this.

**When it is time for a patch (1.X.X) release?**

This release can occur more frequently and in a number of cases:

- A modality field has changed with the validator reflected in this change.
- Additions or updates to the resources around BIDS (i.e. BEP update)
- Specification rendering has been enhanced
- Use case motivated changes

The decision for a patch release will fall onto the judgement call of the maintainer working group. 
