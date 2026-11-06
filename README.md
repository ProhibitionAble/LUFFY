# LUFFY Development Repository

> 🚧 **Development Branch** - This is the main development repository for LUFFY (Learning to Reason Under Off‑Policy Guidance)

## About LUFFY

LUFFY is a framework for training language models with off-policy guidance, combining reinforcement learning techniques with large language model capabilities.

## Current Status

This branch contains active development work. Features may be incomplete or subject to change.

## TODO List

See the complete TODO list below for current development priorities.

### 📝 Complete TODO List

- [ ] **luffy/deepscaler/utils.py:45** - Add logging for API calls and errors
- [ ] **luffy/deepscaler/utils.py:46** - Support batch processing for multiple prompts
- [ ] **luffy/deepscaler/utils.py:47** - Add timeout configuration for API calls
- [ ] **luffy/deepscaler/utils.py:107** - Implement Vertex AI initialization and authentication
- [ ] **luffy/deepscaler/utils.py:108** - Configure safety settings for content generation
- [ ] **luffy/deepscaler/utils.py:109** - Set up GenerativeModel with proper system instructions
- [ ] **luffy/deepscaler/utils.py:110** - Implement retry logic with exponential backoff
- [ ] **luffy/deepscaler/utils.py:111** - Add comprehensive error handling for API access issues
- [ ] **luffy/deepscaler/utils.py:112** - Handle rate limiting and quota management
- [ ] **luffy/deepscaler/utils.py:113** - Implement response validation and text extraction
- [ ] **luffy/deepscaler/utils.py:114** - Add support for different generation configurations
- [ ] **luffy/verl/verl/protocol.py:114** - Optimize memory usage during tensor reshaping
- [ ] **luffy/verl/verl/protocol.py:115** - Add support for different tensor types and shapes
- [ ] **luffy/verl/verl/protocol.py:136** - Optimize tensor view operations for performance
- [ ] **luffy/verl/verl/protocol.py:137** - Add error handling for invalid batch dimensions
- [ ] **luffy/verl/verl/protocol.py:169** - Add consistency check
- [ ] **luffy/verl/verl/protocol.py:265** - Lift restriction when non_tensor_batch and batch are both present
- [ ] **luffy/verl/verl/protocol.py:351** - Decide whether to copy batch/meta info when selecting keys

## Development Notes

- Active development on DeepScaler utilities and Verl protocol components
- Recent changes focus on API client robustness and protocol message handling
- TODO items marked complete reflect implemented functionality in the current dev branch

## Contributing

Please ensure all TODO items are updated when code changes are merged to dev.
