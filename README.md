# Rooftop Solar Asset Performance Analysis

This project analyzes the performance of rooftop solar plants using generation and irradiance (GHI) data.

The objective is to evaluate system efficiency, identify performance issues, and estimate losses at both plant and inverter levels.

### Key Analysis Performed:
- CUF and PR calculation
- Downtime identification
- Inverter-level performance analysis
- Loss estimation (capacity, system, and weather-related)

### Key Learnings:
- PR depends on overall generation and system capacity, not just underperformance days
- Inverter-level analysis is critical for identifying localized issues
- Data validation is essential before drawing conclusions

This project was implemented using Python for automation, while similar analysis can also be performed using Excel.

### Key Insights:

- Plant 1: Performance loss mainly driven by downtime and inverter-level issues
- Plant 2: Initial low performance due to partial inverter availability (~70% capacity)
- Identified underperformance days using generation vs GHI comparison
- Estimated energy losses due to downtime and inverter outages

### Future Improvements:

- Inverter-level PR analysis for deeper diagnostics
- Soiling loss estimation using trend-based approach
- Inclusion of module temperature and POA irradiance for accurate PR calculation
