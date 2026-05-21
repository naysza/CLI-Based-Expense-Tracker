# CLI-Based Expense Tracker

A high-performance command-line interface (CLI) tool engineered in pure C to handle your daily personal finances. This project demonstrates intermediate-to-advanced low-level programming operations, utilizing custom data structures, manual memory layout management, and robust binary file streams.

## Technical Architecture Highlights
- **Dynamic Memory Allocation:** Employs explicit heap memory handling (`malloc` and `realloc`) to automatically double tracking limits dynamically as item counts expand.
- **Binary Stream I/O:** Serializes state structures directly into a localized machine-readable flat binary storage file (`expenses.dat`), executing instantaneous execution workloads.
- **Buffer Safety Optimization:** Features custom input token sanitization that prevents standard keyboard buffer overflow defects common to basic standard library reads (`scanf`).

---

## Getting Started

### Prerequisites
To build and run this application locally, you will need a C compiler installed on your system:
- **Mac:** Command Line Tools (via Xcode) or `gcc` via Homebrew.
- **Linux:** `gcc` (GNU Compiler Collection).
- **Windows:** MinGW or MSVC (Visual Studio Terminal).

### Compilation & Build

1. Open your native Command Terminal window.
2. Navigate directly to your local project directory:
   ```bash
   cd path/to/your/CLI-Based-Expense-Tracker