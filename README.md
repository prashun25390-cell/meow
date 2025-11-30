# Delhi Metro Simulator

## Files
- metro_data.txt → Contains station lists and travel times.
- metro_simulator.py → Main Python program.

## How to Run
1. Put both files in the same folder.
2. Open terminal / cmd.
3. Run:
   python metro_simulator.py

## Features
### 1. Next Train Time
Shows when next train arrives (fixed frequency = 5 min).

### 2. Journey Planner
Given source & destination:
- Finds route on same line if possible.
- Else finds interchange at Janakpuri West.
- Computes total travel time using simple sum of segment times.

## Restrictions Followed
- No pandas, no external libs.
- Only basic file handling: open(), read(), write(), split().
- Simple brute-force logic.
- Very beginner friendly.