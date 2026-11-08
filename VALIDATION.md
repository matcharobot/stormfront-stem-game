# Release verification

Verified on **8 November 2026 (Hong Kong time)** against the supplied IDAT7220 STEM Game assessment details and STEM e-learning Lesson rubric. This records observed requirements and technical checks; it is not a predicted grade.

## Requirement coverage

| Requirement | Evidence in the game |
| --- | --- |
| A STEM topic and identified branch | Urban stormwater design; Environmental / Civil Engineering, integrating science, technology and mathematics. |
| A short game description | The same 20-word description is visible on the title screen and About page. |
| At least two clear objectives | Four objectives on the single About page, with matching experiments, explanations, design tests and final statement. |
| Appropriate learning strategies | Scenario-Based Learning and all five 5E phases are named and connected to concrete activities in About and README. |
| A coherent story with consequential choices | A watermark mystery across three cities and four chapters; persistent engineering choices, stakeholder priorities, a shared budget and five engineering endings. |
| Integrated learning and feedback | Controlled comparison, camera evidence, process explanations, four questions with corrective feedback, and a data-based case statement. |
| Hands-on and collaborative problem solving | Interactive rainfall test, facility placement, simulation/retesting and recorded designer/checker/agreement contributions; explicit solo self-review alternative. |
| Purposeful media and consistent design | 18 Recraft illustrations, SVG flow overlays and charts, optional synthesized rain, consistent fixed 16:9 screens and in-scene navigation. |
| Public game link | The repository's Play link is the GitHub Pages entry point. No learner login is required. |

## Checks completed

- All **576 legal model routes** passed water-balance, capacity, timing, budget and agreement checks; all five endings are reachable.
- Learning and controller tests passed completion gates, supported-answer checks, resumed review tasks, stale-record handling, legacy-save migration and actual report-export generation.
- A fresh browser playthrough followed the README's main route from the prologue through every chapter, solo role review, knowledge check, case statement and **Both lights return** ending.
- That exact route produced **95.4 m³ inflow**, **0 m³ overflow in each district**, **0 m³ remaining storage**, and **4 shared credits remaining**.
- The optional pitch route is covered by the model checks and yields both districts open, **64 m³ in pitch storage** and **6 shared credits remaining**.
- Browser checks found no clipping in the tested design, evidence, interview, role-review, high-river-test and completion screens. Evidence descriptions have 24 stage pixels of clearance. The frame remains 16:9 with no vertical page scrolling.
- All five writing fields retain readable light backgrounds and dark text when hovered, focused and edited. The previous dark-background conflict was corrected.
- Rain can be switched on and off. The tested full walkthrough produced no captured browser errors.
- The release HTML embeds all 18 images and the runtime. It uses no external script sources, analytics or game-data service. The included source archive contains the build script, editable source, tests, media and runtime licence.

## Interpretation limits

Quantities, locations, costs and opening targets are fictional teaching settings. Stored water remains part of the water balance and needs later drainage. Written-entry checks assess completeness; scientific quality is for teacher or peer review. Some designs intentionally illustrate an ineffective or incomplete response. Runtime and route checks do not guarantee an assessment grade.
