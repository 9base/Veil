# Historical 9base Veil packaging work

**Status: Historical Downstream.** Documentation reconstructed from repository history on 8 October 2026.

This repository is derived from [Veil-Framework/Veil](https://github.com/Veil-Framework/Veil). Veil and its framework functionality are upstream work. The verified local scope is Linux distribution installation compatibility, retained on a separate [`pardus-patch` branch](https://github.com/9base/Veil/tree/pardus-patch).

Süleyman Poyraz (`Zaryob`) authored two fork-specific commits on 29 September 2021. [a0eb9243](https://github.com/9base/Veil/commit/a0eb92433ca60395b01cc3571207b7b2d9ba0260) adds Pardus OS detection and dependency/setup handling to `config/setup.sh`, including a guard for Pardus versions below 17. [3dac6fdc](https://github.com/9base/Veil/commit/3dac6fdcba03f2c6f8d05ff9d71bbbfe60b3b84d) adds Pardus to that branch's README. The source change concerns installation support, not original framework or payload development.

Before documentation curation, default `master` had no ahead commits and was 12 behind upstream `master`. `pardus-patch` was two ahead and 12 behind the upstream `master` fallback; no same-named upstream branch existed. Net local changes were limited to `config/setup.sh` and `README.md`. Both branches are preserved, and the historical patch has not been merged into default `master` by this curation.

The patch is meaningful verified downstream adaptation, hence Historical Downstream. No later maintenance is established by the audited history. The inherited upstream [README.md](README.md), notices and branch history remain intact. Installation scripts and framework functionality were not executed, validated or modernized as part of documentation curation.
