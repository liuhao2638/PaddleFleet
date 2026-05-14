# AI-Edited Tests for transformer_enums Module

This directory contains unit tests for PaddleFleet transformer enums,
automatically generated with focus on improving code coverage.

## Test Files

| Test File | Source File | Coverage Target |
|-----------|-------------|-----------------|
| `test_ai_enums.py` | `src/paddlefleet/transformer/enums.py` | Tests for ModelType, LayerType, AttnType, AttnMaskType, AttnBackend |

## Running Tests

```bash
# Run all tests in this directory
python -m pytest tests/single_card_tests/ai_edited_test/transformer_enums/ -v

# Run with unittest
python -m unittest tests.single_card_tests.ai_edited_test.transformer_enums.test_ai_enums
```

## Notes

- Tests use `unittest.TestCase` style
- No CUDA-dependent tests in this module
- Enums tested: ModelType, LayerType, AttnType, AttnMaskType, AttnBackend