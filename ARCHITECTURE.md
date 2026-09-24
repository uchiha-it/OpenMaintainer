# Architecture — Initial Proposal

> This document describes the planned architecture. It is intentionally preliminary.

## Core components

1. **Repository Adapter**
   - Local Git repositories
   - GitHub integration
   - Metadata, issues, pull requests and diffs

2. **Repository Indexer**
   - Source files
   - Tests
   - Documentation
   - Build configuration
   - Dependency metadata

3. **Issue Intelligence**
   - Issue classification
   - Missing-context detection
   - Relevant-file discovery
   - Investigation planning

4. **Investigation Engine**
   - Hypothesis generation
   - Reproduction planning
   - Evidence capture

5. **Execution Sandbox**
   - Isolated command execution
   - Restricted credentials
   - Resource limits
   - Audit logs

6. **Test Generator**
   - Reproduction tests
   - Regression tests
   - Test explanation

7. **Patch Planner**
   - Minimal-change proposals
   - Root-cause explanation
   - Change impact notes

8. **Pull Request Reviewer**
   - Diff analysis
   - Risk detection
   - Test coverage analysis
   - Compatibility and security notes

9. **Human Review Gate**
   - No consequential action without explicit approval
   - Clear evidence and uncertainty

10. **Evaluation Harness**
   - Historical bug benchmarks
   - Human acceptance / rejection signals
   - Accuracy and usefulness metrics

## Design principles

- Human-in-the-loop
- Model-agnostic interfaces
- Reproducibility
- Explicit uncertainty
- Safe-by-default execution
- Auditable actions
- Minimal credential access
