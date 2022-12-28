# example-repository

```mermaid
flowchart LR
    A1((1)) --> B1((2)) -->C1((4))
    style A1 fill:#ff1440,color:#fff
    style B1 fill:#ff1440,color:#fff
    style C1 fill:#ff1440,color:#fff
    A2((1)) --> B2((3)) -->C2((4))
    style A2 fill:#166dda,color:#fff
    style B2 fill:#166dda,color:#fff
    style C2 fill:#166dda,color:#fff
    A2((1)) --> A1((1)) --> B1((2)) B2((3)) --> C1((4)) --> C2((4))
    
```









123
[链接](https://b2b.partcommunity.com/community/knowledge/zh_CN/detail/10753/%E7%BD%97%E9%A9%AC%E6%95%B0%E5%AD%97#knowledge_article)
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
```math
* $-10^9$ <= target <= \$10\^9\$
```
* `2 <= nums.length <= $10^4$`
* ` -10\<sup>9\</sup><= nums[i] <= $10^9$ `
* `$-10^9$ <= target <= $10^9$`
* **哈哈**
* 2 <= nums.length <= $10^4$
* $-10^9$ <= nums[i] <= $10^9$
* $-10^9$ <= target <= $10^9$

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
