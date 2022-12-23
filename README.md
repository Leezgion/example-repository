# example-repository
123

## SubHeader

456
2022/12/17 18:06 update

### code block
```
输入：nums = [2,7,11,15], target = 9
输出：[0,1]
解释：因为 nums[0] + nums[1] == 9 ，返回 [0, 1] 。
```
`输入：nums = [2,7,11,15], target = 9
输出：[0,1]
解释：因为 nums[0] + nums[1] == 9 ，返回 [0, 1] 。`
* $-10^9$ <= target <= $10^9^$
* `2 <= nums.length <= $10^4$`
* ` $-10^9$ <= nums[i] <= $10^9$ `
* `$-10^9$ <= target <= $10^9$`
* **哈哈**
* `-10^9^ <= target <= 10^9^`

```javascript
/**
 * @param {number[]} nums
 * @param {number} target
 * @return {number[]}
 */
var twoSum = function(nums, target) {
    let x;
    let y;
    let arr = [x, y];
    for (x = 0; x < nums.length; x++) {
        for (y = x + 1; y < nums.length ; y++) {
            if (nums[x] + nums[y] == target) {
                arr[0] = x;
                arr[1] = y;
            }
        }
    }
    return arr;
};
```
