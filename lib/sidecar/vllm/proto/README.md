<!--
SPDX-FileCopyrightText: Copyright (c) 2025-2026 NVIDIA CORPORATION & AFFILIATES. All rights reserved.
SPDX-License-Identifier: Apache-2.0
-->

# Vendored vLLM protocol

- Inference source: [`rust/proto/inference.proto`](https://github.com/biswapanda/vllm/blob/553e87bd2852cb4692c17109b35c382d57e87fdb/rust/proto/inference.proto) at `553e87bd2852cb4692c17109b35c382d57e87fdb`
- RL Control source: [`rust/proto/control.proto`](https://github.com/vllm-project/vllm/blob/76ebe5a217d7536a5661272c680f0b1e3a62f5be/rust/proto/control.proto) from [vllm-project/vllm#51316](https://github.com/vllm-project/vllm/pull/51316) at `76ebe5a217d7536a5661272c680f0b1e3a62f5be`
- `inference.proto` SHA-256: `cd3715730dacaae6857a623640537742a3a08716a40e9474c5007a2361403728`
- `control.proto` SHA-256: `db72b0782142054293b07fd48247cc821c048213b9c95dbc37fb0d81dde8f46f`

The files are copied without modification. Update the revision and checksums together. `dynamo-vllm-sidecar` generates and temporarily exports these types for `dynamo-vllm-mocker-server`.
