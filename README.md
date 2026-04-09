# sm/dataquality

A browser-based pre-flight checker for SageMaker fine-tuning datasets.

## Why
SageMaker validates JSONL format, but it does not catch many LLM-specific quality issues that impact training outcomes. `sm/dataquality` adds practical checks before launch so teams can avoid preventable failures and low-quality model behavior.

## Customer
- ML engineers preparing datasets for SageMaker fine-tuning
- Data and model quality teams reviewing readiness before training
- Product teams running repeated tuning cycles who need faster feedback

## Problems This Solves
- Detects schema and formatting issues before training starts
- Flags quality risks such as overlong examples and weak preference-pair divergence
- Highlights dataset size adequacy by technique
- Provides actionable fixes in plain language, directly in the browser
