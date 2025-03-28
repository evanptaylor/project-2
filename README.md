# Large Scale Data Processing: Project 2

Evan Taylor, Andrew Kallmeyer, Gabirel Geyer

### Results

1. Exact F2. Time elapsed:27s. Estimate: 8567966130

2. Tug-of-War F2 Approximation. Width :10. Depth: 3. Time elapsed:20s. Estimate: 7696281566

3.
  Exact F0. Time elapsed:25s. Estimate: 7406649
  
  BJKST Algorithm. Bucket Size:4. Trials:3. Time elapsed:18s. Estimate: 8388608.0
  
  BJKST Algorithm. Bucket Size:5. Trials:3. Time elapsed:21s. Estimate: 6291456.0
  
  BJKST Algorithm. Bucket Size:4. Trials:5. Time elapsed:28s. Estimate: 4194304.0
  
  BJKST Algorithm. Bucket Size:5. Trials:5. Time elapsed:30s. Estimate: 6291456.0


4. We found our implementations to be successful in estimating F0 and F2. We found that we could run BJKST with a bucket size of 4 and still get accurate results, although these results became worse as we increased the depth to 5. We submitted trials with both 4 and 5 for reference. 

