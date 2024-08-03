# Calculate co-effecienct of Variance

### Instructions

1. Install:

         pip install get-cov2


2. Calculate the co-effecient of variance

      #### import libraries
         from get_cov2 import main
         from random import randint
      #### calculation of co-effecient of variance
         # generate a series
         series = [randint(1,10) for i in range(5) ]
         # calculate the co-effecient of variance
         cov = main.gc(series).cov()
