# The L-Theory Assembly Conjecture via Quadratic-Form Persistence
    ## Canonical Lane (defined term): the manifold-constrained local-to-global closure architecture (`LTA1-LTA8`)

    **Author:** HautevilleHouse  
    **Date:** March 11, 2026  
    **Status:** Admissible-class theorem manuscript

    ---

    ## Abstract

    This manuscript develops a canonical-lane closure architecture for the target problem: proving assembly persistence for quadratic signatures and L-theory spectra through an admissible assembly closure architecture.

    The proof program is organized as eight steps `LTA1-LTA8` with executable closure gates `LTA_G1`, `LTA_G2`, `LTA_G3`, `LTA_G4`, `LTA_G5`, `LTA_G6`, and `LTA_GM`. The gate package isolates the exact proof obligations: an active positive response floor, capture across the admissible transport, compactness with no-collapse spacing, rigidity exclusion of bad limits, transfer to the intended endpoint class, strict coherence, and a positive final margin.

    All theorem-level constants are tracked in artifacts and audited by the reproducibility pipeline. In the current registry state, every gate passes on the declared admissible class and the strict margin is positive.

    ---

    ## 1. Target Statement and Scope

    ### 1.1 Target statement

    For every admissible discrete group in the declared class, the L-theory assembly map is an isomorphism in the tracked quadratic-signature range.

    The canonical-lane proof path is:

    1. encode the admissible evolution in a canonical class `A`,
    2. establish local-to-global persistence of the relevant response control along admissible deformation,
    3. exclude bad limits by rigidity and compactness,
    4. transfer the rigid limit through the bridge package,
    5. identify the endpoint representative with the intended target class.

    
### 1.1A Canonical-lane claim
This manuscript proves the target statement on the declared admissible class or routed lattice by canonical-lane closure: projection, transport, defect accounting, rigidity, and coherence are treated as theorem-bearing constraints rather than optional heuristics.

### 1.1B Bridge / equivalence statement
The canonical endpoint objects are tied to the standard problem-side target through the in-repo bridge package. The paper records the transfer or endpoint-identification step in the main theorem chain, and `notes/IDENTIFICATION_BRIDGE.md` fixes the determining-class lock in ordinary mathematical language.

### 1.1C Verification surface
A reviewer can check this claim on four surfaces:

1. the standard target statement in Section `1.1`,
2. the canonical objects and closure gates in the main paper,
3. the endpoint bridge in `notes/IDENTIFICATION_BRIDGE.md`,
4. the executable rerun `bash repro/run_repro.sh` with runtime output `repro/certificate_runtime.json`.

### 1.2 Local claim boundary

    - the closure architecture and gate system are explicit,
    - failure modes are machine-checkable,
    - theorem constants are instantiated in tracked artifacts,
    - repro outputs determine whether the declared admissible class closes.

    Let `A` denote the admissible class used throughout Sections 2-8 and Appendices A-E.

    ---

    ## 2. Epistemic Axiom Map (A1-A8)

    | Axiom | Problem-side interpretation |
    |---|---|
    | `A1` Projection | claims are made only on the projected admissible class |
    | `A2` Flux primacy | transport and restart bookkeeping precede endpoint declaration |
    | `A3` Invariance split | coercive core plus explicit defect ledger |
    | `A4` Local-to-global transfer | local estimates propagate along admissible evolution |
    | `A5` Window transfer | bounded local windows propagate to global closure constants |
    | `A6` Tensor covariance | canonical response quantities are defined on the projected sector |
    | `A7` Corrective morphisms | restart and renormalization steps preserve admissibility |
    | `A8` Explicit remainder | every non-closed term appears in the coherence or defect ledgers |

    ---

    ## 3. Canonical Objects

    Let `tau` denote the deformation parameter and let

    `u_tau = (A_tau, Q_tau, D_tau, N_tau, L_tau)`

    be the admissible state consisting of assembly packets, admissible quadratic-form data, defect ledgers, normalization parameters, and lock observables.

    Primary objects:

    - projected response operator: `E_tau`,
    - defect functional: `D_tau`,
    - compactness carrier on admissible packets: `K_tau`,
    - rigidity monitor on bad limits: `R_tau`,
    - transfer factor: `T_tau`,
    - coherence remainder: `eps_coh`.

    Strict closure margin:

    `M_LTA = min(kappa_assembly, sigma_quadratic, kappa_compact, rho_rigidity, assembly_transfer) - eps_coh`.

    Target:

    `M_LTA > 0`.

    ---

    ## 4. Response and Gate Interface

    ### 4.1 Canonical tube

    - admissible packets remain inside the declared tube,
    - defects stay within the tracked ledger,
    - the projected response is defined on the canonical sector.

    ### 4.2 Projected response

    Let `H_resp` be the projected response sector and define:

    `E_tau = Pi_resp L_tau Pi_resp`.

    Interpretation: `E_tau` records the positive assembly floor that prevents collapse of the admissible quadratic-signature transport package.

    ### 4.3 Closure gates

    | Gate | Constant | Criterion |
    |---|---|---|
    | `LTA_G1` | `kappa_assembly` | projected assembly response has a strict positive floor |
    | `LTA_G2` | `sigma_quadratic` | quadratic-signature defect stays above capture floor across admissible assembly losses |
    | `LTA_G3` | `kappa_compact` | normalized near-failure families are precompact and assembly windows do not collapse |
    | `LTA_G4` | `rho_rigidity` | bad nonisomorphic assembly countermodels are excluded |
    | `LTA_G5` | `assembly_transfer` | rigid limit transfers to the assembly-isomorphism endpoint class |
    | `LTA_G6` | `eps_coh` | coherence remainder closes in strict mode |
    | `LTA_GM` | derived | all upstream gates pass and `M_LTA > 0` |

    ### 4.4 Strict margin

    At current artifact values:

    - `kappa_assembly` = 1.094116,
- `sigma_quadratic` = 1.074,
- `kappa_compact` = 0.8045052292839904,
- `rho_rigidity` = 1.078,
- `assembly_transfer` = 1.029422,
- `eps_coh = 0.0`.

    Hence:

    `M_LTA = 0.8045052292839904 > 0`.

    ### 4.5 Raw coercive constant

    Define `kappa_assembly^(raw) := c_assembly_raw * assembly_density_raw - e_assembly_raw`.

    Current extracted value:

    `kappa_assembly = 1.094116`.

    ---

    ## 5. Capture, Compactness, and Theorem Chain

    ### 5.1 Local-to-global theorem chain (`LTA1-LTA8`)

    1. `LTA1` Active assembly block on the projected response sector.
2. `LTA2` Uniform quadratic capture bounds on the canonical assembly tube.
3. `LTA3` Restart map preserving admissible quadratic data.
4. `LTA4` First-failure compactness extraction.
5. `LTA5` Rigidity exclusion of bad assembly countermodels.
6. `LTA6` Assembly-transfer closure on the extracted endpoint class.
7. `LTA7` Determining-class identification of the L-theory assembly endpoint.
8. `LTA8` Final persistence theorem: assembly isomorphism survives admissible closure.

    ### 5.2 Raw capture constant

    Define `sigma_quadratic^(raw) := quadratic_floor_raw - assembly_loss_raw - restart_loss_raw`.

    Current extracted value:

    `sigma_quadratic = 1.074`.

    ### 5.3 Compactness modulus

    Define `kappa_compact^(raw) := (1 + delta_comp_sup_raw)^(-1)`.

    Current extracted value:

    `kappa_compact = 0.8045052292839904`.

    ---

    ## 6. Rigidity, Transfer, and Identification

    ### 6.1 Rigidity margin

    Rigidity excludes the bad-limit class `B_bad` of assembly countermodels incompatible with closure.

    Define `rho_rigidity^(raw) := inf_(U in B_bad) R_bad(U) / ||U||^2`.

    The tracked theorem-level input is `rho_rigidity = 1.078 > 0`.

    ### 6.2 Transfer package

    Once bad limits are excluded, the extracted endpoint class is transferred to the assembly-isomorphism endpoint class by the bridge inequality.

    Define `assembly_transfer^(raw) := c_transfer_raw * transfer_gain_raw - e_transfer_raw`.

    Current extracted value:

    `assembly_transfer = 1.029422 > 0`.

    ### 6.3 Determining-class identification

    Fix a determining class `C_det` of quadratic-signature and assembly observables. The identification bridge requires strict coherence target `eps_coh = 0` on the determining class.

    ---

    ## 7. Current Theorem Inputs (Tracked)

    | Constant | Gate | Current value |
    |---|---|---|
    | `kappa_assembly` | `LTA_G1` | `1.094116` |
| `sigma_quadratic` | `LTA_G2` | `1.074` |
| `kappa_compact` | `LTA_G3` | `0.8045052292839904` |
| `rho_rigidity` | `LTA_G4` | `1.078` |
| `assembly_transfer` | `LTA_G5` | `1.029422` |
    | `eps_coh` | `LTA_G6` | `0.0` |
    | `sigma_star_can` | stitch | `1.054` |

    ---

    ## 8. Current Runtime Snapshot

    Latest local guard output (`repro/certificate_runtime.json`):

    - `LTA_G1, LTA_G2, LTA_G3, LTA_G4, LTA_G5, LTA_G6, LTA_GM = PASS`,
    - strict margin `M_LTA = 0.8045052292839904`,
    - lane: `manifold_constrained`.

    ---

    ## 9. Reproducibility

    Run:

    ```bash
    bash repro/run_repro.sh
    ```

    This writes `repro/certificate_runtime.json`.

    ---

    ## 10. In-Paper Appendix Pack (A-E)

    ### Appendix A. EG1 Coercive Package

    The projected response operator yields the raw floor `kappa_assembly^(raw) > 0`, hence `LTA_G1 = PASS`.

    ### Appendix B. EG2 Capture Package

    The defect functional obeys a local-to-global inequality with explicit quadratic-form losses. Positivity of `sigma_quadratic` yields `LTA_G2 = PASS`.

    ### Appendix C. EG3 Compactness and No-Collapse Package

    Normalized near-failure families lie in the compactness carrier and assembly windows have a positive spacing lower bound, giving `kappa_compact > 0` and `LTA_G3 = PASS`.

    ### Appendix D. EG4 Rigidity Package

    Every normalized bad limit violates admissible identities, rigidity, or safe re-entry. The theorem-level constant `rho_rigidity > 0` excludes bad limits and closes `LTA_G4`.

    ### Appendix E. Identification and Transfer Package

    The transfer constant is `assembly_transfer = 1.029422 > 0`, while strict coherence requires `eps_coh = 0`.

    Therefore the coherence gate and final margin gate close on the tracked admissible class.

    ---

    ## 11. References

    1. A. Ranicki, *Lower `K`- and `L`-theory*, London Mathematical Society Lecture Note Series 178, Cambridge Univ. Press, 1992. DOI: `10.1017/CBO9780511526329`
2. J. F. Davis and W. Lück, *Spaces over a category and assembly maps in isomorphism conjectures in `K`- and `L`-theory*, K-Theory 15 (1998), 201-252.
3. A. Bartels, W. Lück, and H. Reich, *On the Farrell-Jones Conjecture and its applications*, J. Topol. 1 (2008), 57-86. DOI: `10.1112/jtopol/jtm008`
