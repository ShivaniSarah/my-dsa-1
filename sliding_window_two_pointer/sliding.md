if count of subarrays == k

prefix count approach

 for (int num : nums) {
            sum += num;
            if (prefixSumCount.containsKey(sum - goal)) {
                count += prefixSumCount.get(sum - goal);
            }
            prefixSumCount.put(sum, prefixSumCount.getOrDefault(sum, 0) + 1);
        }



if count of all subarrays <= k

res += right - left + 1
