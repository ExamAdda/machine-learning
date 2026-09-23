# 🖥️ Operating Systems Roadmap

> A structured roadmap to learn Operating Systems from fundamentals to advanced concepts including process management, CPU scheduling, synchronization, memory management, file systems, Linux internals, virtualization, and performance optimization.

---

### Basic OS

- [Roadmap](https://tech.examadda.org/os/roadmap)
- [Introduction of OS](https://tech.examadda.org/os/introduction-to-operating-systems)
- [Functions of OS](https://tech.examadda.org/os/functions-of-an-operating-system)
- [Types of OS](https://tech.examadda.org/os/types-of-operating-systems)
  - [Batch](https://tech.examadda.org/os/types-of-operating-systems)
  - [Time Sharing](https://tech.examadda.org/os/types-of-operating-systems-1)
  - [Distributed](https://tech.examadda.org/os/types-of-operating-systems-distributed-operating-systems)
  - [Network](https://tech.examadda.org/os/types-of-operating-systems-network-operating-systems)
- [Goals of OS](https://tech.examadda.org/os/goals-of-an-operating-system)
- [OS Architecture](https://tech.examadda.org/os/monolithic-kernel-operating-system-architecture)
  - [Monolithic Kernel](https://tech.examadda.org/os/monolithic-kernel-operating-system-architecture)
  - [Microkernel Architecture](https://tech.examadda.org/os/microkernel-architecture-operating-systems)
  - [Hybrid Kernel](https://tech.examadda.org/os/hybrid-kernel-architecture-operating-systems)
  - [Layered Architecture](https://tech.examadda.org/os/layered-architecture-operating-systems)
- [Core Concepts](https://tech.examadda.org/os/kernel-vs-user-mode)
  - [Kernel vs User Mode](https://tech.examadda.org/os/kernel-vs-user-mode)
  - [Interrupts, Traps, Exceptions](https://tech.examadda.org/os/interrupts-traps-exceptions)
  - [System Calls](https://tech.examadda.org/os/system-calls)
  - [Boot Process](https://tech.examadda.org/os/boot-process)

### Process Management

- [Introduction](https://tech.examadda.org/os/process-management-introduction)
- [Process Concept](https://tech.examadda.org/os/process-concept-operating-systems)
- [Process State Diagram](https://tech.examadda.org/os/process-state-diagram-operating-systems)
- [Process Control Block (PCB)](https://tech.examadda.org/os/process-control-block-pcb)
- [Process Operations](https://tech.examadda.org/os/process-creation)
  - [Process Creation](https://tech.examadda.org/os/process-creation)
  - [Process Termination](https://tech.examadda.org/os/process-concept-operating-systems-1)
- [Context Switching](https://tech.examadda.org/os/context-switching-operating-systems)

### CPU Scheduling Algorithms

- [Introduction](https://tech.examadda.org/os/cpu-scheduling-concept)
  - [Scheduling Concept](https://tech.examadda.org/os/cpu-scheduling-concept)
  - [Scheduling Criteria](https://tech.examadda.org/os/cpu-scheduling-criteria)
- [Algorithms](https://tech.examadda.org/os/cpu-scheduling-fcfs)
  - [First Come First Serve](https://tech.examadda.org/os/cpu-scheduling-fcfs)
  - [Shortest Job First](https://tech.examadda.org/os/cpu-scheduling-shortest-job-first-sjf)
  - [Shortest Remaining Time First](https://tech.examadda.org/os/cpu-scheduling-srtf-algorithm)
  - [Priority Scheduling](https://tech.examadda.org/os/cpu-scheduling-priority-scheduling-algorithm)
  - [Round Robin](https://tech.examadda.org/os/cpu-scheduling-round-robin-rr-algorithm)
  - [Multilevel Queue Scheduling](https://tech.examadda.org/os/cpu-scheduling-multilevel-queue-scheduling)
  - [Multilevel Feedback Queue Scheduling](https://tech.examadda.org/os/cpu-scheduling-multilevel-feedback-queue-mlfq)
- [Advanced Algorithms](https://tech.examadda.org/os/cpu-scheduling-preemptive-vs-non-preemptive)
  - [Preemptive vs Non-Preemptive](https://tech.examadda.org/os/cpu-scheduling-preemptive-vs-non-preemptive)
  - [Starvation & Aging](https://tech.examadda.org/os/cpu-scheduling-starvation-and-aging)
  - [Scheduling in Real-Time Systems](https://tech.examadda.org/os/cpu-scheduling-real-time-systems)

### Process Synchronization

- [Introduction](https://tech.examadda.org/os/process-synchronization-critical-section-problem)
  - [Critical Section Problem](https://tech.examadda.org/os/process-synchronization-critical-section-problem)
  - [Race Condition](https://tech.examadda.org/os/process-synchronization-race-condition)
- [Synchronization Tools](https://tech.examadda.org/os/process-synchronization-mutex-locks)
  - [Mutex Locks](https://tech.examadda.org/os/process-synchronization-mutex-locks)
  - [Semaphores](https://tech.examadda.org/os/process-synchronization-semaphores)
  - [Monitors](https://tech.examadda.org/os/process-synchronization-monitors)
  - [Condition Variables](https://tech.examadda.org/os/process-synchronization-condition-variables-1)
- [Advanced](https://tech.examadda.org/os/process-synchronization-spinlocks)
  - [Spinlocks](https://tech.examadda.org/os/process-synchronization-spinlocks)
  - [Read-Write Locks](https://tech.examadda.org/os/process-synchronization-read-write-locks)
  - [Barriers](https://tech.examadda.org/os/process-synchronization-barriers)
- [Classic Problems](https://tech.examadda.org/os/process-synchronization-producer-consumer-problem)
  - [Producer-Consumer Problem](https://tech.examadda.org/os/process-synchronization-producer-consumer-problem)
  - [Dining Philosophers Problem](https://tech.examadda.org/os/process-synchronization-dining-philosophers-problem)
  - [Readers-Writers Problem](https://tech.examadda.org/os/process-synchronization-readers-writers-problem)
  - [Sleeping Barber Problem](https://tech.examadda.org/os/process-synchronization-sleeping-barber-problem)

### Deadlocks

- [Introduction](https://tech.examadda.org/os/deadlocks-deadlock-concept)
- [Necessary Conditions](https://tech.examadda.org/os/deadlocks-mutual-exclusion)
  - [Mutual Exclusion](https://tech.examadda.org/os/deadlocks-mutual-exclusion)
  - [Hold and Wait](https://tech.examadda.org/os/deadlock-hold-and-wait-os)
  - [No Preemption](https://tech.examadda.org/os/deadlock-no-preemption-os)
  - [Circular Wait](https://tech.examadda.org/os/deadlock-circular-wait-os)
- [Handling Methods](https://tech.examadda.org/os/deadlocks-deadlock-prevention)
  - [Deadlock Prevention](https://tech.examadda.org/os/deadlocks-deadlock-prevention)
  - [Deadlock Avoidance](https://tech.examadda.org/os/deadlocks-deadlock-avoidance)
  - [Deadlock Detection](https://tech.examadda.org/os/deadlocks-deadlock-detection)
  - [Deadlock Recovery](https://tech.examadda.org/os/deadlocks-deadlock-recovery)
- [Algorithms](https://tech.examadda.org/os/deadlocks-resource-allocation-graph)
  - [Resource Allocation Graph](https://tech.examadda.org/os/deadlocks-resource-allocation-graph)
  - [Banker's Algorithm](https://tech.examadda.org/os/deadlocks-bankers-algorithm)
- [Advanced](https://tech.examadda.org/os/deadlocks-deadlock-vs-livelock)
  - [Deadlock vs Livelock](https://tech.examadda.org/os/deadlocks-deadlock-vs-livelock)

### Memory Management

- [Introduction](https://tech.examadda.org/os/memory-management-concepts-os)
  - [Memory Management Concepts](https://tech.examadda.org/os/memory-management-concepts-os)
  - [Address Binding](https://tech.examadda.org/os/address-binding-os)
  - [Logical vs Physical Address](https://tech.examadda.org/os/logical-vs-physical-address-os)
- [Techniques](https://tech.examadda.org/os/dynamic-loading-linking-os)
  - [Dynamic Loading & Linking](https://tech.examadda.org/os/dynamic-loading-linking-os)
  - [Swapping](https://tech.examadda.org/os/swapping-os)
- [Allocation](https://tech.examadda.org/os/contiguous-memory-allocation-os)
  - [Contiguous Memory Allocation](https://tech.examadda.org/os/contiguous-memory-allocation-os)
- [Fragmentation](https://tech.examadda.org/os/internal-fragmentation-os)
  - [Internal Fragmentation](https://tech.examadda.org/os/internal-fragmentation-os)
  - [External Fragmentation](https://tech.examadda.org/os/external-fragmentation-os)

### Paging

- [Introduction](https://tech.examadda.org/os/paging-concept-os)
  - [Paging Concept](https://tech.examadda.org/os/paging-concept-os)
  - [Page Table](https://tech.examadda.org/os/page-table-os)
  - [Address Translation](https://tech.examadda.org/os/address-translation-paging-os)
- [Advanced](https://tech.examadda.org/os/multilevel-paging-os)
  - [Multilevel Paging](https://tech.examadda.org/os/multilevel-paging-os)
  - [Inverted Page Table](https://tech.examadda.org/os/inverted-page-table-os)
  - [Translation Lookaside Buffer](https://tech.examadda.org/os/tlb-os)

### Segmentation

- [Introduction](https://tech.examadda.org/os/segmentation-concept-operating-systems)
- [Segment Table](https://tech.examadda.org/os/segment-table-operating-systems)
- [Segmentation with Paging](https://tech.examadda.org/os/segmentation-with-paging-os)

### Virtual Memory

- [Introduction](https://tech.examadda.org/os/virtual-memory-operating-systems)
  - [Virtual Memory Concept](https://tech.examadda.org/os/virtual-memory-operating-systems)
  - [Demand Paging](https://tech.examadda.org/os/demand-paging-os)
  - [Page Fault Handling](https://tech.examadda.org/os/page-fault-handling-os)
- [Advanced Concepts](https://tech.examadda.org/os/copy-on-write-os)
  - [Copy-on-Write](https://tech.examadda.org/os/copy-on-write-os)
  - [Thrashing](https://tech.examadda.org/os/thrashing-os)
- [Page Replacement Algorithms](https://tech.examadda.org/os/fifo-page-replacement-operating-systems)

### File System

- [Introduction](https://tech.examadda.org/os/file-concept-operating-systems)
  - [File Concept](https://tech.examadda.org/os/file-concept-operating-systems)
  - [File Attributes](https://tech.examadda.org/os/file-attributes-operating-systems)
  - [File Operations](https://tech.examadda.org/os/file-operations-os)
  - [File Types](https://tech.examadda.org/os/file-types-operating-systems)
- [Access Methods](https://tech.examadda.org/os/sequential-file-access-os)
  - [Sequential](https://tech.examadda.org/os/sequential-file-access-os)
  - [Direct](https://tech.examadda.org/os/direct-file-access-os)
  - [Indexed](https://tech.examadda.org/os/indexed-file-access-os)
- [Directory Structure](https://tech.examadda.org/os/single-level-directory-os)
  - [Single Level](https://tech.examadda.org/os/single-level-directory-os)
  - [Two Level](https://tech.examadda.org/os/two-level-directory-structure-operating-systems)
  - [Tree Structure](https://tech.examadda.org/os/tree-structured-directory-os)
  - [Acyclic Graph](https://tech.examadda.org/os/acyclic-graph-directory-os)
- [File System Implementation](https://tech.examadda.org/os/file-allocation-methods)
  - [File Allocation Methods](https://tech.examadda.org/os/contiguous-file-allocation-os)
    - [Contiguous](https://tech.examadda.org/os/contiguous-file-allocation-os)
    - [Linked](https://tech.examadda.org/os/linked-file-allocation-os)
    - [Indexed](https://tech.examadda.org/os/indexed-file-allocation-os)
  - [Advanced](https://tech.examadda.org/os/journaling-file-systems-operating-systems)
    - [Journaling File Systems](https://tech.examadda.org/os/journaling-file-systems-operating-systems)
    - [Log-Structured File Systems](https://tech.examadda.org/os/log-structured-file-systems-lfs-operating-systems)
    - [File System Consistency & Recovery](https://tech.examadda.org/os/file-system-consistency-recovery-os)

### Disk Management

- [Introduction](https://tech.examadda.org/os/disk-structure-in-operating-systems)
  - [Disk Structure](https://tech.examadda.org/os/disk-structure-in-operating-systems)
- [Disk Scheduling Algorithms](https://tech.examadda.org/os/fcfs-disk-scheduling)
  - [FCFS](https://tech.examadda.org/os/fcfs-disk-scheduling)
  - [SSTF](https://tech.examadda.org/os/sstf-disk-scheduling-1)
  - [SCAN](https://tech.examadda.org/os/scan-disk-scheduling-elevator-algorithm)
  - [C-SCAN](https://tech.examadda.org/os/c-scan-disk-scheduling-circular-scan)
  - [LOOK](https://tech.examadda.org/os/look-disk-scheduling)
  - [C-LOOK](https://tech.examadda.org/os/c-look-disk-scheduling-os)
- [Other Topics](https://tech.examadda.org/os/disk-formatting-in-operating-systems)
  - [Disk Formatting](https://tech.examadda.org/os/disk-formatting-in-operating-systems)
  - [Disk Partitioning](https://tech.examadda.org/os/disk-partitioning-in-operating-systems)
  - [RAID Structure](https://tech.examadda.org/os/raid-redundant-array-of-independent-disks)

### I/O System

- [Introduction](https://tech.examadda.org/os/io-hardware-operating-systems)
  - [I/O Hardware](https://tech.examadda.org/os/io-hardware-operating-systems)
  - [I/O Devices](https://tech.examadda.org/os/io-devices-operating-systems)
  - [I/O Interface](https://tech.examadda.org/os/io-interface-operating-systems)
- [Concepts](https://tech.examadda.org/os/device-drivers-operating-systems)
  - [Device Drivers](https://tech.examadda.org/os/device-drivers-operating-systems)
  - [Interrupt Handling](https://tech.examadda.org/os/interrupt-handling-operating-systems)
  - [Direct Memory Access (DMA)](https://tech.examadda.org/os/direct-memory-access-operating-systems)

### Protection and Security

- [Introduction](https://tech.examadda.org/os/protection-concept-operating-systems)
  - [Protection Concept](https://tech.examadda.org/os/protection-concept-operating-systems)
  - [Access Control](https://tech.examadda.org/os/access-control-operating-systems)
  - [Access Matrix](https://tech.examadda.org/os/access-matrix-operating-systems-1)
  - [Capability-Based System](https://tech.examadda.org/os/capability-based-systems-operating-systems)
- [Security](https://tech.examadda.org/os/authentication-operating-systems)
  - [Authentication](https://tech.examadda.org/os/authentication-operating-systems)
  - [Encryption](https://tech.examadda.org/os/encryption-operating-systems)
  - [Security Threats](https://tech.examadda.org/os/security-threats-in-operating-systems)
- [Advanced](https://tech.examadda.org/os/sandboxing-operating-systems)
  - [Sandboxing](https://tech.examadda.org/os/sandboxing-operating-systems)
  - [OS-level Security (SELinux basics)](https://tech.examadda.org/os/os-level-security-operating-systems)

### Threads

- [Thread Concept](https://tech.examadda.org/os/thread-concept-operating-systems)
- [User vs Kernel Threads](https://tech.examadda.org/os/user-vs-kernel-threads-operating-systems)
- [Multithreading Models](https://tech.examadda.org/os/multithreading-models-operating-systems)
- [Thread Libraries](https://tech.examadda.org/os/posix-threads-pthreads-operating-systems)
- [Thread Scheduling](https://tech.examadda.org/os/thread-scheduling-operating-systems)

### Advanced Memory Management

- [Buddy System](https://tech.examadda.org/os/buddy-system-memory-allocation-operating-systems)
- [Slab Allocation](https://tech.examadda.org/os/slab-allocation-operating-systems)
- [Memory-Mapped Files](https://tech.examadda.org/os/memory-mapped-files-operating-systems)
- [NUMA](https://tech.examadda.org/os/numa-operating-systems-memory-architecture)

### Distributed Systems

- [Introduction](https://tech.examadda.org/os/distributed-systems-operating-systems)
  - [Distributed Systems Concept](https://tech.examadda.org/os/distributed-systems-operating-systems)
  - [Client-Server Model](https://tech.examadda.org/os/client-server-model-distributed-systems)
  - [Peer-to-Peer Model](https://tech.examadda.org/os/peer-to-peer-model-distributed-systems)
- [Mechanisms](https://tech.examadda.org/os/distributed-file-systems-operating-systems)
  - [Distributed File Systems](https://tech.examadda.org/os/distributed-file-systems-operating-systems)
  - [Remote Procedure Call (RPC)](https://tech.examadda.org/os/remote-procedure-call-rpc-distributed-systems)

### Virtualization

- [Introduction](https://tech.examadda.org/os/virtual-machine-concept-operating-systems)
- [Hypervisor](https://tech.examadda.org/os/hypervisor-operating-systems)
- [Modern](https://tech.examadda.org/os/containerization-docker-operating-systems)
  - [Containerization (Docker concept)](https://tech.examadda.org/os/containerization-docker-operating-systems)

### Modern OS Concepts

- [Multicore Processing](https://tech.examadda.org/os/multicore-processing-operating-systems)
- [Cloud Operating Systems](https://tech.examadda.org/os/cloud-operating-systems)
- [Mobile Operating Systems](https://tech.examadda.org/os/mobile-operating-systems)

### Linux Internals

- [Linux Architecture](https://tech.examadda.org/os/linux-architecture-operating-systems)
- [Process Management in Linux](https://tech.examadda.org/os/process-management-linux-operating-systems)
- [Scheduling (CFS Scheduler basics)](https://tech.examadda.org/os/linux-cfs-scheduler-operating-systems)
- [Memory Management in Linux](https://tech.examadda.org/os/memory-management-linux-operating-systems)
- [System Calls in Linux](https://tech.examadda.org/os/system-calls-linux-operating-systems)

### Performance & Optimization

- [Throughput vs Latency](https://tech.examadda.org/os/throughput-vs-latency-operating-systems)
- [CPU Utilization](https://tech.examadda.org/os/cpu-utilization-operating-systems)
- [Load Balancing](https://tech.examadda.org/os/load-balancing-operating-systems-distributed-systems)
- [Bottlenecks](https://tech.examadda.org/os/bottlenecks-operating-systems-performance)

---

## 🗺️ Learning Path

```text
Basic OS
    ↓
Process Management
    ↓
CPU Scheduling
    ↓
Process Synchronization
    ↓
Deadlocks
    ↓
Memory Management
    ↓
Paging & Segmentation
    ↓
Virtual Memory
    ↓
File System
    ↓
Disk Management
    ↓
I/O System
    ↓
Protection & Security
    ↓
Threads
    ↓
Advanced Memory Management
    ↓
Distributed Systems
    ↓
Virtualization
    ↓
Modern OS Concepts
    ↓
Linux Internals
    ↓
Performance & Optimization
    ↓
🚀 Advanced Operating Systems
