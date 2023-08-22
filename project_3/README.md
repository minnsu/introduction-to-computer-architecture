# Project 3 - Spike RISC-V Simulator

## Goal 1: Find best cache configuration
- Using --dc=[sets]:[ways]:[block_size] options
- Total data cache capacity is fixed to 16KB. Also, block size is fixed to 64 bytes.
- Therefore, possible cache configuration is
  ```
  --dc=1:256:64
  --dc=2:128:64
  --dc=4:64:64
  --dc=8:32:64
  --dc=16:16:64
  --dc=32:8:64
  --dc=64:4:64
  --dc=128:2:64
  --dc=256:1:64
  ```
## Goal 2: Modify cache replacement algorithm to LRU
- Find and modify the appropriate file that solves Goal 2.
- As with Goal 1, find the best cache configurations.

## Submit: Put goal1.txt and goal2.txt into simulator's directory
