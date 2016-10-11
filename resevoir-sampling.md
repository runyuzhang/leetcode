# Resevoir Sampling

When we read the second node, we can decide if we replace the result 'r' or not. The possibility is 1\/2. So we just generate a random number between 0 and 1, and check if it is equal to 1. If it is 1, replace 'r' as the value of the current node, otherwise we don't touch 'r', so its value is still the value of head.

