# AI portfolio repository review

**Repository completion: 39/39.**

**LAST REPOSITORY COMPLETED: [Feedback Quality Evaluator](https://github.com/devissaputra/feedback_quality_evaluator) — 39/39.**

The last repository commit for the main pass is `21ba2cfefa7309c1919df484ac20fcc8e6fe3aff`. Subsequent follow-up commits integrate reproduced LSTM and TalkMoves results. Review date: 26 September 2026.

## Delivered

- Both portfolio pages revised: 9 AI Engineering entries and 30 AI in Education entries.
- Eight featured empirical entries use two paragraphs; the other 31 use one paragraph.
- Every repository has two new scientific SVG figures, a calculation guide, source-linked evidence and reproducible figure generation.
- All 39 README front sections revised; 13 existing working papers expanded or corrected. Existing references and detailed documentation retained where applicable.
- Scientific figures distinguish external-data results, synthetic demonstrations and illustrative arithmetic. They do not fabricate measurements.

## Substantive corrections

| Repository | Correction and evidence |
|---|---|
| Multimodal Self-Regulation Lab | Replaced in-sample classifier AUC with a shared stratified 70/30 holdout; imputation/scaling fit only on training data. The rank-fusion comparator is explicitly transductive. |
| LSTM Time Series | Replaced future-borrowing interpolation with past-only forward fill; full 20-epoch run and CI succeeded. Updated results, figures and working paper. [Run](https://github.com/devissaputra/lstm_time_series/actions/runs/36235069744). |
| Feedback Quality Evaluator | Constant identical ratings now produce undefined kappa rather than an unjustified value of one; exact agreement remains one. Regression tests pass. |
| Classroom Discourse Intelligence | Completed the empirical study, detected duplicate archive copies, added content deduplication/grouping, and reran. Final analysis: 565 groups and 175,129 teacher utterances. [Corrected run](https://github.com/devissaputra/classroom_discourse_intelligence/actions/runs/36250532574). |

## Verification scope

- 27 bundled demonstrations executed successfully.
- 441 checks passed in 17 existing unittest suites during the initial review. Additional regression checks cover the three calculation fixes; the feedback suite subsequently passed 43 tests.
- 28 existing pytest-style test functions were executed directly, with supported temporary-directory arguments; no failures. This is not reported as a full pytest-suite run.
- 121 independent stored-result arithmetic checks passed within declared floating-point tolerances. These cover selected summary statistics, confusion-derived metrics and paired differences, not every possible mathematical claim.
- All 78 SVGs parse and regenerate from their stated source files. Text-bound checks found no overflow in the main pass; representative figures were rendered and inspected.
- Page structure checks confirm paragraph and figure counts. Local browser screenshots could not be produced because the browser executable was unavailable; no local desktop/mobile rendering pass is claimed.

The review does not claim that all 39 projects were independently reproduced from raw data or scientifically validated. Synthetic policy rules remain prototypes. Most pre-existing empirical results were inspected against their committed evidence; the corrected LSTM and TalkMoves experiments were fully rerun during this review.

## Repository completion register

| # | Repository | Main pass |
|---:|---|---|
| 1 | [classification_calibration](https://github.com/devissaputra/classification_calibration) | Complete |
| 2 | [anomaly_detection](https://github.com/devissaputra/anomaly_detection) | Complete |
| 3 | [explainable_ai](https://github.com/devissaputra/explainable_ai) | Complete |
| 4 | [mini_transformers_sequences](https://github.com/devissaputra/mini_transformers_sequences) | Complete |
| 5 | [imbalanced_learning](https://github.com/devissaputra/imbalanced_learning) | Complete |
| 6 | [pca_clustering](https://github.com/devissaputra/pca_clustering) | Complete |
| 7 | [mlp_neural_network](https://github.com/devissaputra/mlp_neural_network) | Complete |
| 8 | [cnn_image_classification](https://github.com/devissaputra/cnn_image_classification) | Complete |
| 9 | [lstm_time_series](https://github.com/devissaputra/lstm_time_series) | Complete |
| 10 | [knowledge_tracing_benchmark](https://github.com/devissaputra/knowledge_tracing_benchmark) | Complete |
| 11 | [causal_learning_analytics](https://github.com/devissaputra/causal_learning_analytics) | Complete |
| 12 | [misconception_aware_rag](https://github.com/devissaputra/misconception_aware_rag) | Complete |
| 13 | [responsible_aied_evaluation](https://github.com/devissaputra/responsible_aied_evaluation) | Complete |
| 14 | [genai_learning_observatory](https://github.com/devissaputra/genai_learning_observatory) | Complete |
| 15 | [teacher_ai_assessment](https://github.com/devissaputra/teacher_ai_assessment) | Complete |
| 16 | [privacy_preserving_learning_analytics](https://github.com/devissaputra/privacy_preserving_learning_analytics) | Complete |
| 17 | [multimodal_self_regulation_lab](https://github.com/devissaputra/multimodal_self_regulation_lab) | Complete |
| 18 | [learning_design_process_mining](https://github.com/devissaputra/learning_design_process_mining) | Complete |
| 19 | [hybrid_intelligence_lab](https://github.com/devissaputra/hybrid_intelligence_lab) | Complete |
| 20 | [explanation_faithfulness_aied](https://github.com/devissaputra/explanation_faithfulness_aied) | Complete |
| 21 | [collaborative_reasoning_analytics](https://github.com/devissaputra/collaborative_reasoning_analytics) | Complete |
| 22 | [cognitive_offloading_analytics](https://github.com/devissaputra/cognitive_offloading_analytics) | Complete |
| 23 | [classroom_discourse_intelligence](https://github.com/devissaputra/classroom_discourse_intelligence) | Complete |
| 24 | [adaptive_socratic_tutor](https://github.com/devissaputra/adaptive_socratic_tutor) | Complete |
| 25 | [instructor_insight_engine](https://github.com/devissaputra/instructor_insight_engine) | Complete |
| 26 | [learner_state_sequence_model](https://github.com/devissaputra/learner_state_sequence_model) | Complete |
| 27 | [multimodal_learning_analytics](https://github.com/devissaputra/multimodal_learning_analytics) | Complete |
| 28 | [constructive_alignment_auditor](https://github.com/devissaputra/constructive_alignment_auditor) | Complete |
| 29 | [assessment_design_lab](https://github.com/devissaputra/assessment_design_lab) | Complete |
| 30 | [learning_experiment_platform](https://github.com/devissaputra/learning_experiment_platform) | Complete |
| 31 | [lesson_design_agent](https://github.com/devissaputra/lesson_design_agent) | Complete |
| 32 | [learner_agency_simulator](https://github.com/devissaputra/learner_agency_simulator) | Complete |
| 33 | [competency_gap_intelligence](https://github.com/devissaputra/competency_gap_intelligence) | Complete |
| 34 | [workplace_learning_recommender](https://github.com/devissaputra/workplace_learning_recommender) | Complete |
| 35 | [training_transfer_analytics](https://github.com/devissaputra/training_transfer_analytics) | Complete |
| 36 | [engagement_early_warning](https://github.com/devissaputra/engagement_early_warning) | Complete |
| 37 | [curriculum_knowledge_graph](https://github.com/devissaputra/curriculum_knowledge_graph) | Complete |
| 38 | [self_regulated_learning_copilot](https://github.com/devissaputra/self_regulated_learning_copilot) | Complete |
| 39 | [feedback_quality_evaluator](https://github.com/devissaputra/feedback_quality_evaluator) | **COMPLETE — LAST** |
