# Maximum-Width-Ramp
**Precompute Right Maximums:**

Create an array rightMax where each element rightMax[i] holds the maximum value from nums[i] to the end of the array. This helps efficiently compare nums[i] with elements to the right of it.
**Two-pointer Approach:**

Use two pointers, left and right. Move right forward while nums[left] <= rightMax[right].
Once the condition is false, update the maximum ramp width (maxVal) and increment left. Then, reset right to left + maxVal + 1 to optimize the search.
**Max Ramp Calculation:**

The maximum ramp width is calculated and returned by comparing each valid pair.
