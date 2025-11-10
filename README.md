README.md

# r2pq-precompiles

R2PQ Precompiles provides optimized verification functions for ML-DSA, SLH-DSA, and other PQ signature primitives, designed for integration into blockchain runtimes or precompile hosts.

## Purpose
- High-performance PQ signature verification  
- Bytecode-level or FFI-level precompile modules  
- Gas-cost calibration references  
- Standardized ABI for runtimes to call PQ verifiers  

## Structure

/ml-dsa           # ML-DSA verifier implementations /slh-dsa          # SLH-DSA verifier implementations /common           # Shared buffers, hashing, serialization /ffi              # (optional) language bindings

## Status
✅ Initialized  
🚧 PQ verification code not yet added

# Legal
R2PQ is open-source under the Apache-2.0 License.  
R2PQ™ is a trademark of Eric James Newman.  
See `LICENSE`, `NOTICE`, and `TRADEMARKS.md` for details.
