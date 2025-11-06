# System Patterns

---
## Clean Architecture Pattern
*   [2025-07-12 17:20:04]
*   [2025-07-12 15:44:04]
**Description:** The Portal application follows Clean Architecture with Domain, Application, Infrastructure, and Persistence layers
**Tags:** architecture, design-pattern

---
## MCP Integration Pattern
*   [2025-07-12 17:20:04]
*   [2025-07-12 15:44:04]
**Description:** Use MCP (Model Context Protocol) for external service integrations like GitHub, SonarCloud, and IDE interactions
**Tags:** integration, mcp, external-services
---

---
## Core Architecture Patterns
*   [2025-07-12 17:20:04]
*   [2025-07-12 16:23:23]
- **Pipeline Architecture**: Sequential processing stages enabling efficient transformation of graphics data
- **Fluent vs Imperative APIs**: Design patterns for graphics operations balancing readability and performance
- **Depth-First vs Breadth-First Processing**: Strategic approaches for optimizing cache locality and vectorization
---

---
## Memory Management Patterns
*   [2025-07-12 17:20:04]
*   [2025-07-12 16:23:23]
- **Array Pooling**: High-performance array reuse through ArrayPool<T> for reduced GC pressure
- **Span<T> Zero-Copy Operations**: Stack-only ref structs for efficient memory slicing without allocations
- **Large Object Heap Optimization**: Strategies for managing textures and large graphics buffers
---

---
## GPU Acceleration Patterns
*   [2025-07-12 17:20:04]
*   [2025-07-12 16:23:23]
- **ComputeSharp Integration**: C#-to-HLSL transpilation for DirectX compute shaders
- **ILGPU Cross-Platform**: GPU computing with JIT compilation for CUDA, OpenCL, and CPU backends
- **Memory Transfer Optimization**: Pinned memory and async patterns for CPU-GPU data movement
---

---
## Performance Optimization Patterns
*   [2025-07-12 17:20:04]
*   [2025-07-12 16:23:23]
- **SIMD Vectorization**: Leveraging Vector<T> and hardware intrinsics for parallel operations
- **Asynchronous Processing**: Task-based patterns for parallel graphics pipeline execution
- **Compression Strategy Selection**: Content-adaptive compression using WebP, AVIF, and JPEG XL
---

---
## Cross-Platform Graphics Patterns
*   [2025-07-12 17:20:04]
*   [2025-07-12 16:23:23]
- **SkiaSharp Integration**: Cross-platform 2D graphics with hardware acceleration
- **ImageSharp Pure Managed**: Managed image processing without native dependencies
- **Framework Selection Strategy**: Choosing appropriate graphics libraries based on requirements
---
