
Part IV

#38 1. Looked through the code a couple times to understand the program.
    2. Set breakpoints at each method in Pallet class, ran through it using step and step into.
    3. Errors found from step 2, a) aBrick.getHeight() % height, * instead of %
                                 b) Base weight not added during getWeight().
                                 c) Surface area formula for brick is wrong, adds side1 twice.
