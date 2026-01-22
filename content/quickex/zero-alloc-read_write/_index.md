---
title: 
toc: false
---

## Zero Alloc Reading and Writing

No allocations when reading and writing to the wire, these examples can be more complex to adapt in real world applications without memory or ring leaking, use with caution.

By zero allocations we mean no extra allocations on the received or sent data, we operate on a “view” to the kernel ring buffer for the received data and provide a byte* to the kernel for the data to be sent.