# Methodology / Metodologia

## Purpose / Objetivo
Demonstrate a physician's workflow for reviewing synthetic medical AI responses: clinical accuracy, reasoning, safety, factuality, completeness, and clarity. / Demonstrar avaliação médica de respostas sintéticas de IA.

## Protocol / Protocolo
1. Author a fully synthetic case and a fixed prompt.
2. Present two explicitly **simulated** candidate responses (A/B).
3. Record independent evaluator scores (0–4 per dimension), safety classification, preference, rationale, and improvement feedback.
4. Compute weighted totals using the [rubric](rubrics/clinical_ai_rubric_v1.md).
5. Preserve original evaluation verbatim, separate from any proposed reference or editorial feedback.
6. Document guideline references and limitations.
7. For future real-model studies, record model/version, date, settings, prompts, raw outputs, and evaluator independence.

## Limitations / Limitações
This is a **training portfolio**, not a prospective clinical study, validated benchmark, regulatory assessment, or real-world model-performance claim. The reference assessment was generated within the exercise, not by an independent adjudication panel. A set of ten synthetic cases is insufficient to establish clinical safety, efficacy, or generalizability. No real patient data are used.

## Planned cases / Casos planejados
CLIN-001 acute chest pain (completed); CLIN-002 fabricated evidence; CLIN-003 unsafe recommendation; CLIN-004 incomplete clinical answer; CLIN-005 pairwise response ranking; CLIN-006 test interpretation; CLIN-007 uncertainty calibration; AUD-008 guideline adherence; AUD-009 eligibility logic; AUD-010 privacy and sensitive data handling.
