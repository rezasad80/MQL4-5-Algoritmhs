# My MQL Trading Tools Collection

Advanced trading utilities for MetaTrader 4 & 5  
✔ Professional-grade Expert Advisors (EAs)  
✔ Custom technical indicators  
✔ Practical trading scripts  
✔ Optimized for algorithmic trading

## Key Features
- Ready-to-use MQL4/MQL5 solutions
- Carefully tested trading algorithms
- Customizable parameters for all tools
- Clear documentation for easy implementation

## Categories
| Folder         | Contents                          |
|----------------|-----------------------------------|
| `/Experts`     | Automated trading robots          |
| `/Indicators`  | Custom technical indicators       |
| `/Scripts`     | Utility scripts for trade management |
| `/Libraries`   | Shared MQL include files          |

All tools include detailed configuration instructions in their headers.

## Experts


## Indicators

### MA Crossover Alert Indicator
**`MA_Crossover_by_RezaSadeghi.mq5`**  
Advanced moving average crossover detection with multi-alert functionality.

#### Key Features:
- **Dual MA Monitoring**: Tracks any two MAs (SMA/EMA/LWMA) with configurable periods
- **Smart Visual Alerts**:
  - Colored arrows (↑ for bullish crossover, ↓ for bearish crossover)
  - Customizable arrow styles (size/color/position)
- **Multi-Notification System**:
  -  MetaTrader pop-up alerts
  -  Email notifications (if configured)
  -  Mobile push notifications
- **Multi-Timeframe Support**: Works on all timeframes (M1 to MN)
