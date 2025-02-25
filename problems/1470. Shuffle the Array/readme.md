### 1470. Shuffle the Array
**Easy**

<br />
Given the array `nums` consisting of `2n` elements in the form <code>[x<sub>1</sub>,x<sub>2</sub>,...,x<sub>n</sub>,y<sub>1</sub>,y<sub>2</sub>,...,y<sub>n</sub>]</code>.

Return the array in the form <code>[x<sub>1</sub>,y<sub>1</sub>,x<sub>2</sub>,y<sub>2</sub>,...,x<sub>n</sub>,y<sub>n</sub>]</code>.
<br />

**Example 1:**

<pre>
<b>Input:</b> nums = [2,5,1,3,4,7], n = 3
<b>Output:</b> [2,3,5,4,1,7] 
<b>Explanation:</b> Since x1=2, x2=5, x3=1, y1=3, y2=4, y3=7 then the answer is [2,3,5,4,1,7].
</pre>

**Example 2:**

<pre>
<b>Input:</b> nums = [1,2,3,4,4,3,2,1], n = 4
<b>Output:</b> [1,4,2,3,3,2,4,1]
</pre>

**Example 3:**

<pre>
<b>Input:</b> nums = [1,1,2,2], n = 2
<b>Output:</b> [1,2,1,2]
</pre>
<br />

**Constraints:**

- 1 <= n <= 500
- nums.length == 2n
- <code>1 <= nums[i] <= 10<sup>3</sup></code>
