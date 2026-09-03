<!--
SPDX-FileCopyrightText: Copyright (c) 2025-2026 NVIDIA CORPORATION & AFFILIATES. All rights reserved.
SPDX-License-Identifier: Apache-2.0
-->

# Vendored vLLM protocol

- Inference source: [`rust/proto/inference.proto`](https://github.com/vllm-project/vllm/blob/3d1f5cee1552b8208f3009c75f8bc856f27e0eff/rust/proto/inference.proto) at `3d1f5cee1552b8208f3009c75f8bc856f27e0eff`, extended with the preprocessed multimodal source from [`25cbc76295`](https://github.com/biswapanda/vllm/commit/25cbc76295fa68b219f6271180017e018827ff55)
- RL Control source: [`rust/proto/control.proto`](https://github.com/vllm-project/vllm/blob/2991f864083fdd5c60aa140d4fe1a561585a85dc/rust/proto/control.proto) from [vllm-project/vllm#51316](https://github.com/vllm-project/vllm/pull/51316) and [vllm-project/vllm#53204](https://github.com/vllm-project/vllm/pull/53204) at `2991f864083fdd5c60aa140d4fe1a561585a85dc`
- `inference.proto` SHA-256: `c307cd33c3d73c7803ce03b6e9357a23c1edfee69d2193fcb17d13dba879a986`
- `control.proto` SHA-256: `c8363fd4397187a44e667d3d04ada30401e078ab6763ed5144f674184dd8d787`

The control file is copied without modification. The inference file carries only the documented compatibility extension above. Update the revisions and checksums together. `dynamo-vllm-sidecar` generates and temporarily exports these types for `dynamo-vllm-mocker-server`.
