# CPU Scheduling Algorithms - Python Implementation

## Overview

This project implements five fundamental CPU scheduling algorithms with clear code, visual timeline representations, and detailed performance statistics.

## Implemented Algorithms

1. **First-Come, First-Served (FCFS)** - Non-preemptive, O(n) complexity
2. **Shortest Job Next (SJN)** - Non-preemptive, O(n log n) complexity  
3. **Priority Scheduling** - Non-preemptive, priority-based
4. **Round Robin (RR)** - Preemptive, time quantum-based
5. **Multi-level Queue Scheduling** - Non-preemptive, multiple priority queues

## Project Structure

```
cpuSchedulingPython/
├── main.py                    # Main program entry point
├── parser.py                  # Input parsing and data management
├── algorithms.py              # Algorithm implementations
├── output.py                  # Output formatting and display
├── test_example.py           # Test suite
└── Reports/                  # Detailed documentation
    ├── PROJECT_REPORT.md        # Complete project analysis
    ├── COMPLETE_PROJECT_SUMMARY.md  # Project overview
    ├── APPENDIX_A_CODE_ANALYSIS.md  # Code analysis
    ├── APPENDIX_B_ALGORITHM_COMPARISON.md  # Algorithm comparison
    └── APPENDIX_C_TROUBLESHOOTING.md       # Troubleshooting guide
```

## Performance Comparison

| Algorithm | Avg Wait Time | Avg Turnaround | CPU Utilization |
|-----------|---------------|----------------|-----------------|
| FCFS | 8.6 | 8.6 | 100% |
| SJN | 4.2 | 8.2 | 100% |
| Priority | 6.8 | 10.8 | 100% |
| Round Robin | 7.4 | 11.4 | 100% |
| Multi-Level | 5.6 | 9.6 | 100% |

## Documentation

For detailed information, see the comprehensive documentation in the `Reports/` directory:

- **[Project Report](Reports/PROJECT_REPORT.md)** - Complete project analysis and implementation details
- **[Code Analysis](Reports/APPENDIX_A_CODE_ANALYSIS.md)** - In-depth code examination
- **[Algorithm Comparison](Reports/APPENDIX_B_ALGORITHM_COMPARISON.md)** - Performance and characteristics analysis
- **[Troubleshooting Guide](Reports/APPENDIX_C_TROUBLESHOOTING.md)** - Common issues and solutions

## Contributing

This is an educational project. Feel free to report issues, suggest improvements, or add new algorithms. 
